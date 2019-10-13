<template>
  <div class="container has-text-centered">
    <div class="box">
      <h1 class="title">This is Home</h1>

      <router-link class="button is-primary" :to="{ name: 'login' }">Login</router-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>