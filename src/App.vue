<template>
  
  <div class="text-lg bg-red-500 text-white p-4 shadow">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>

  <RouterView />
</template>

<script>
  export default{
    name:"Vue3-Blog"
  }
</script>