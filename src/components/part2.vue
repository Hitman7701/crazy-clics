<script setup>
const dislayName = () => {
  console.log('Je mappelle Yassine')
}

const displayName2 = (name) => {
  alert(`Je m'appelle ${name}`)
}
</script>

<template>
  <section class="part2">
    <button @click="dislayName()">Comment t'appelles-tu ?</button>

    <button @click="displayName2('Yassine')">Comment t'appelles-tu ?</button>
  </section>
</template>

<style scoped></style>
