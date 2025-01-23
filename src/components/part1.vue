<template>
  <section class="part1">
    <button v-on:click="console.log('Hello World !')">Affiche un message dans la console</button>
    <button @click="console.log('Bienvenue au Reacteur !')">
      Affiche un autre message dans la console
    </button>
  </section>
</template>

<style scoped></style>
