<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
const name = 'Batman';
const greet = 'Hello';
const channel = 'Codevolution';


</script>

<template>
  <header>
    <div class="wrapper">
      <div class="">{{ name }} - {{ greet }}</div>
      <div v-text="channel"></div>
    </div>
  </header>

</template>

<style scoped>

</style>
