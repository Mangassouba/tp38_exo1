<script setup>
import { ref } from 'vue';



</script>

<template>
<div class="container">
  <h1>Liste des employés</h1>
  <ol>
  <li>Mangassouba</li>
  <li>Bankole</li>
  <li>Seme</li>
  <li>traoré</li>
  <li>Ly</li>
  <li>Ba</li>
  <li>Baradji</li>
  <li>Cissé</li>
  </ol>
</div>

</template>

<style scoped>
.container{
  width: 100%;
  height: 100vh;
  background-color: lightseagreen;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.container ol li{
  color: #fff;
  font-weight: bold;
  font-size: 1.2em;
  cursor: pointer;
}
.container ol li:hover{
  color: #000;
}
</style>
