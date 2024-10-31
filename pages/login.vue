<template>
  <div>
    <h1>Login Page</h1>
    <button @click="login">Login</button>
  </div>
</template>

<script>
export default {
  methods: {
    login() {
      this.$store.dispatch('login')
      this.$router.push('/dashboard') 
    }
  }
}
</script>
