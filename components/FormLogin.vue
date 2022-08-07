<template>
    <div class="row row-cols-auto">
        <div class="col-12">
            <img class="position-absolute" style="z-index: -1;width: 100px" src="../assets/header-login.png"
                alt="header" />
            <div class="d-flex justify-content-center my-5">
                <img src="../assets/logo.png" alt="logo" style="width: 100px" />
            </div>
        </div>
        <div class="col-12 my-4">
            <div class="d-flex justify-content-center">
                <div class="container" style="max-width: 350px">
                    <div class="my-3">
                        <h4>Login</h4>
                        <span class="text-muted" style="font-size: 14px">Please sign in to continue.</span>
                    </div>
                    <div class="my-4">
                        <v-form>
                            <span>User ID</span>
                            <v-text-field v-model="userId" :error-messages="userIdErrors" placeholder="User ID" required
                                @input="$v.userId.$touch()" @blur="$v.userId.$touch()"></v-text-field>
                            <span>Password</span>
                            <v-text-field v-model="password" :error-messages="passwordErrors" placeholder="Password"
                                required @input="$v.password.$touch()" @blur="$v.password.$touch()" type="password">
                            </v-text-field>
                            <div class="d-flex justify-content-end">
                                <v-btn class="btn btn-primary px-5" @click="submit">
                                    login
                                </v-btn>
                            </div>
                        </v-form>
                    </div>
                    <div class="my-5 text-center">
                        <span class="text-muted" style="font-size: 12px;">Don't have an account? <nuxt-link to="/"
                                style="color: red;">Sign Up</nuxt-link></span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import { validationMixin } from 'vuelidate'
import { required } from 'vuelidate/lib/validators'

export default {
    name: 'FormLogin',
    mixins: [validationMixin],

    validations: {
        userId: { required },
        password: { required },
    },

    data: () => ({
        userId: '',
        password: '',
    }),

    computed: {
        userIdErrors() {
            const errors = []
            if (!this.$v.userId.$dirty) return errors
            !this.$v.userId.required && errors.push('User ID is required.')
            return errors
        },
        passwordErrors() {
            const errors = []
            if (!this.$v.password.$dirty) return errors
            !this.$v.password.required && errors.push('Password is required')
            return errors
        },
    },

    methods: {
        submit() {
            if (this.$v.userId !== "" && this.$v.password !== "") {
                if (this.$v.userId.$model == this.$parent.dummyAccount.userid && this.$v.password.$model == this.$parent.dummyAccount.password) {
                    alert('Success')
                    this.$emit('authenticated', true)
                    this.$router.replace('/dashboard')
                } else {
                    alert(`Wrong User ID: ${this.$parent.dummyAccount.userid} or Password: ${this.$parent.dummyAccount.password}`)
                }
            } else {
                alert('Required User ID or Password')
            }
        },
    },
}
</script>

<style>
.btn-primary {
    background: blueviolet !important;
    border: none;
    color: white !important;
    border-radius: 50px;
}
</style>