<template>
  <div>
  <button v-on:click="saludo = !saludo">Saluda</button>
  <p v-if="saludo">My saludo es HOLI</p>
  <p v-if="!saludo">My saludo es CHAITO</p>
</div>
</template>

<script>
export default {
  data() {
    return {
      saludo: true,
    };
  },
};
</script>
