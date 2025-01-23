<script setup>
const colors = { bleue: '#23b8d3', violette: '#a519a5', orange: '#ffa500', verte: '#44f178' }
const displayColor = (color) => {
  alert(`Il s'agit de la couleur ${color} dont le code hexadécimal est
'${colors[color]}'.'`)
}
</script>

<template>
  <section class="part3">
    <div><h2>De quelle couleur s'agit-il ?</h2></div>

    <div>
      <button id="blue-button" @click="displayColor('bleue')"></button>
      <button id="purple-button" @click="displayColor('violette')"></button>
      <button id="orange-button" @click="displayColor('orange')"></button>
      <button id="green-button" @click="displayColor('verte')"></button>
    </div>
  </section>
</template>
