<script setup>
// <!-- PART2 -->

const dislayName = () => {
  console.log('Je mappelle Yassine')
}

const displayName2 = () => {
  alert("Je m'appelle Yassine")
}

// <!-- PART 3 -->

const colors = {
  bleue: '#23b8d3',
  violette: '#a519a5',
  orange: '#ffa500',
  verte: '#44f178',
}

const displayColor = (color) => {
  alert(`Il s'agit de la couleur ${color} dont le code hexadécimal est '${colors[color]}'.'`)
}

// PART4

const randomNumber = (max) => {
  alert(Math.floor(Math.random() * max))
}
</script>

<template>
  <main>
    <!-- PART1 -->
    <h1>Crazy clics</h1>
    <section class="part1">
      <button v-on:click="console.log('Hello World !')">Affiche un message dans la console</button>
      <button @click="console.log('Bienvenue au Reacteur !')">
        Affiche un autre message dans la console
      </button>
    </section>

    <!-- PART2 -->

    <section class="part2">
      <button @click="dislayName()">Comment t'appelles-tu ?</button>

      <button @click="displayName2()">Comment t'appelles-tu ?</button>
    </section>

    <!-- PART3 -->

    <section class="part3">
      <div><h2>De quelle couleur s'agit-il ?</h2></div>

      <div>
        <button id="blue-button" @click="displayColor('bleue')"></button>
        <button id="purple-button" @click="displayColor('violette')"></button>
        <button id="orange-button" @click="displayColor('orange')"></button>
        <button id="green-button" @click="displayColor('verte')"></button>
      </div>
    </section>

    <!-- PART4 -->

    <section class="part4">
      <div><button @click="randomNumber(100)">Chiffre surprise</button></div>
    </section>
  </main>
</template>

<style scoped></style>
