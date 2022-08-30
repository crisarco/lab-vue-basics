<template>
  <h1>{{ myString('Cris') }}</h1>
  <br>
  <div v-for='project in projects' :key='project.id'>
    <h3>{{ project.title }}</h3>
    <p>{{ project.description }}</p>
  </div>
</template>

<script>
export default {
  name: 'MyNewComponent',
  methods: {
    myString(nombre) {
      return `Este es el nuevo componente de ${nombre}`;
    },
  },
  data() {
    return {
      projects: [
        {
          id: 0,
          title: 'Project 1',
          description: 'Esta es la descripción del proyecto1',
        },
        {
          id: 1,
          title: 'Project 2',
          description: 'Esta es la descripción del proyecto2',
        },
        {
          id: 2,
          title: 'Project 3',
          description: 'Esta es la descripción del proyecto3',
        },
      ],
    };
  },
};
</script>
