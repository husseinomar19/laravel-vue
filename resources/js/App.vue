<template>
    <div>
    
        <nav>
      <RouterLink to="/">Home</RouterLink> |
      <RouterLink to="/about">About</RouterLink>
    </nav>
    
    <RouterView />

      <example-component></example-component>
      <h1>test</h1>
    </div>
  </template>
  
  <script>
  import ExampleComponent from './src/components/ExampleComponent.vue';
  import { RouterLink, RouterView } from 'vue-router';
  export default {
    components: {
      ExampleComponent
    }
  }
  </script>
  