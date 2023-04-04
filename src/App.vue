<template>
  <nav>
    <router-link to="/">Home</router-link> | <router-link to="/about">About</router-link> |
    <router-link to="/contact">Contact</router-link>
  </nav>
  <main>
    <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
      <router-view />
      <p class="text-gray-500 text-lg">Vue and Tailwind CSS in action</p>
    </div>
  </main>
</template>

<style>
@import './style.css';
</style>
