<script setup>
const randomNumber = (max) => {
  alert(Math.floor(Math.random() * max))
}
</script>

<template>
  <section class="part4">
    <div><button @click="randomNumber(100)">Chiffre surprise</button></div>
  </section>
</template>
