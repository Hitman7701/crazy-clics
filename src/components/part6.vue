<script setup>
const displayNetwork = (app) => {
  alert(`Il s'agit du réseau ${app}.`)
}
</script>

<template>
  <section class="part6">
    <button @click="displayNetwork('GitHub')">
      <font-awesome-icon :icon="['fab', 'github']" />
    </button>
    <button @click="displayNetwork('Linkedin')">
      <font-awesome-icon :icon="['fab', 'linkedin']" />
    </button>
    <button @click="displayNetwork('Instagram')">
      <font-awesome-icon :icon="['fab', 'instagram']" />
    </button>
  </section>
</template>
