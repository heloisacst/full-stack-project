<template>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/tutorials">Tutorials</router-link>
      <router-link to="/add">Add</router-link>
    </nav>
</template>

<script>

    export default {
        components: 'NavBar'
    }

</script>

<style>

nav {

  display: flex;
  gap: 10px;
  background-color: #363636;
}

nav a {
  font-weight: bold;
  color: white;
  background-color: #363636;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>