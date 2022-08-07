<template>
  <div>
    <div>
      <router-link v-if="authenticated" to="/login" v-on:click.native="logout()" replace>Logout</router-link>
    </div>
    <router-view @authenticated="setAuthenticated" />
  </div>
</template>

<script>

export default {
  data: () => ({
    authenticated: false,
  }),

  mounted() {
    if (!this.authenticated) {
      this.$router.replace('/login')
    }
  },

  methods: {
    setAuthenticated(status) {
      this.authenticated = status;
    },
  }
}
</script>

<style>
</style>