<template>
  <div v-for="text in 3" :key="text.id" class="flex bg-white w-[650] shadow mx-auto mt-2">
    <div class="p-2 flex-shrink-0">
        <img class="shadow" height="250" width="250" src="https://picsum.photos/536/354" alt="img1">
    </div>
    <div class="ml-2 p-2">
      <div class="font-bold text-lg text-purple-600">กรุงเทพมหานคร</div>
      <div class="text-sm">
       
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";
import { onMounted } from '@vue/runtime-core';

export default {
  name: "HomePage",
  setup(){
    onMounted(()=>{
      axios.get("http://localhost:3000/posts").then((res)=>console.log(res))
    })
  }
};
</script>
<style></style>
