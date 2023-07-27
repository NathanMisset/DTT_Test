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
    <nav>
      <img id="logo" src="./assets/imgs/img_logo_dtt@3x.png">
      <ul>
        <li class="ActiveHeaderItem">Houses</li>
        <li class="InactiveHeaderItem">About</li>
      </ul>
    </nav>
   </header>
  <main>
    <h1>H1</h1>
    <h2>H2</h2>
    <p class="inputfieldtitle">inputfieldtitle </p>
    <p class="emptystatemessage">emptystatemessage </p>
    <p class="listinginformation">listinginformation</p>
    <p class="inputfield">inputfield</p>
  </main>
</template>


