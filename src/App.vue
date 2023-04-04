<template>
  <div>
    <NavBar />
    <main>
      <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
        <router-view />
        <p class="text-gray-500 text-lg">Vue and Tailwind CSS in action</p>
      </div>
    </main>
  </div>
</template>

<script lang="ts">
import NavBar from '@/components/NavBar.vue';
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'App',
  components: {
    NavBar
  }
})
</script>

<style>
@import './style.css';
</style>
