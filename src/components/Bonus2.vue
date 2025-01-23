<script setup>
const colorsList = [
  'bleu',
  'vert',
  'rose',
  'orange',
  'violet',
  'marron',
  'jaune',
  'noir',
  'rouge',
  'gris',
]

const randomColor = () => {
  let i = Math.floor(Math.random() * colorsList.length)

  alert(`${colorsList[i]}`)
}
</script>

<template>
  <section class="bonus2">
    <button @click="randomColor()">Couleur surprise</button>
  </section>
</template>
