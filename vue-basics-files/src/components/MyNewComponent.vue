<template>
  <h1>{{ myString('Cris') }}</h1>
</template>

<script>
export default {
  name: 'MyNewComponent',
  methods: {
    myString(nombre) {
      return `Este es el nuevo componente de ${nombre}`;
    },
  },
};
</script>
