<template>
  <NavigationHeader/>
  <h1> Hola Mundo</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavigationHeader from '@/components/NavigationHeader.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: { NavigationHeader }, // Aquí declaras el componente Navbar
});
</script>
