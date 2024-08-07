<script setup lang="ts">
import { RouterView } from 'vue-router'
import FooterBlock from '@/components/inc/FooterBlock.vue';

</script>

<template>

  <div class="container">

    <RouterView />
  </div>


  <footer-block/>

</template>



<style>

body{

  background-color: #7c5dff !important;
}

</style>
