<template>
  <div class="app">
    <h1>
      typescript
    </h1>
    <Ts />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Ts from "./components/Ts.vue";

export default defineComponent({
  name: "App",
  components: {
  
    Ts},
});
</script>

<style>
body{ 
  background:#000;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #004488;
  margin-top: 60px;
}
h1{
  text-transform:uppercase;
}
h2{
  color:#ff0f0f;
}
</style>
