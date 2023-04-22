<template>
  <div class="home">
    <h1>Home</h1>
    <h1>{{msg}}</h1>
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png">
    <h1>This is a personal website about myself</h1>
    <h1>Chrisjohn Crisostomo</h1>


  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      msg: 'Welcome to my VueJs project'
    }
  }
}
</script>

<style scoped>

</style>