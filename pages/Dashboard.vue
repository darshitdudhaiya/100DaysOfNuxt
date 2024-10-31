<template>
  <div>
    <h1>Welcome to the Dashboard!</h1>
    <button @click="logout">Logout</button>
  </div>
</template>

<script>
export default {
  middleware: 'auth',
  methods: {
    logout() {
      this.$store.dispatch('logout')
      this.$router.push('/login') 
    }
  }
}
</script>
