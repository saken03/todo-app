<!-- <script setup>
import { ref } from 'vue'

function filter(chosen) {
  console.log(chosen + ' is working...')
  if (chosen == 'all') {
    const all = document.querySelector('.all');
    console.log(all);
  }
}

</script> -->
<template>
  <main>
      <p>
        #todo
      </p>
      
      <div class="filters">
        <button class="all">All</button> 
        <button class="active">Active</button>
        <button class="completed">Completed</button>
      </div>

      <div class="input">
        <input type="text">
        <button>Add</button>
      </div>

      <div class="output">
        
      </div>
  </main>
</template>