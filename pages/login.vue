<template>
    <FormLogin />
</template>

<script>
import FormLogin from '../components/FormLogin'
export default {
    name: 'login',
    components: {
        FormLogin
    },
    data() {
        return {
            dummyAccount: {
                userid: 'user22',
                password: '123'
            }
        }
    },
}
</script>

<style>
</style>