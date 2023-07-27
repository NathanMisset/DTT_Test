<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
// import { useCounterStore } from "./stores/counter";
import NavigationHeader  from "./components/NavigationHeader.vue";
// const store = useCounterStore();
// store.count++;
// store.increment(2);
</script>

<template>
  <header>
    <div id="start">
        <img id="logo" src="./assets/imgs/img_logo_dtt@3x.png">
    </div>
    <div id="center"></div>
    <div id="end"></div>
   </header>
  <main>
    <h1>H1</h1>
    <h2>H2</h2>
    <p class="inputfieldtitle">inputfieldtitle </p>
    <p class="emptystatemessage">emptystatemessage </p>
  </main>
</template>


