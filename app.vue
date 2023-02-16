<template>
  <div class="container">
    <button @click="hello">Hello</button>
    <button @click="error">Error</button>
  </div>
</template>

<script setup lang="ts">
  import LogRocket from 'logrocket';

  LogRocket.init('fwiqiw/pylyp-test');

  function hello(){
    console.log('Hello')
  }
  function error(){
    console.log(undefined()())
  }
</script>


<style>
  .container{
    min-width: 100vw;
    min-height: 100vh;
    background-color: black;
  }
</style>