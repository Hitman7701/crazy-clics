<script setup>
const colorsList = [
  { name: 'bleu', hexa: '#0B71BA' },
  { name: 'vert', hexa: '#39B639' },
  { name: 'orange', hexa: '#EA8512' },
  { name: 'violet', hexa: '#721D7D' },
  { name: 'marron', hexa: '#713928' },
  { name: 'jaune', hexa: '#DED94B' },
  { name: 'noir', hexa: '#1C1C18' },
  { name: 'rouge', hexa: '#F11919' },
  { name: 'gris', hexa: '#9C9696' },
]

const randomColorBis = () => {
  let i = Math.floor(Math.random() * colorsList.length)

  alert(
    `Vous obtenez du ${colorsList[i].name} dont le code hexadécimal est '${colorsList[i].hexa}'.`,
  )
}
</script>
<template>
  <section class="bonus3">
    <button @click="randomColorBis()">Couleur surprise version bis</button>
  </section>
</template>
