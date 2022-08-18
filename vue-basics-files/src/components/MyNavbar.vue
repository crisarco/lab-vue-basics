<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
</template>

<script>

export default {
  name: 'MyNavbar',
};
</script>

<style>
.barra-nav {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
