<template>
  <MyNavbar />
  <router-view />
  <MyNewComponent />
  <LabIteration3 />
  <MyFooter />
</template>

<script>
import MyNavbar from '@/components/MyNavbar.vue';
import MyFooter from '@/components/MyFooter.vue';
import MyNewComponent from '@/components/MyNewComponent.vue';
import LabIteration3 from '@/components/LabIteration3.vue';

export default {
  name: 'App',
  components: {
    MyNavbar,
    MyFooter,
    MyNewComponent,
    LabIteration3,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
