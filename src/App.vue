<script setup>
import NavBarComponent from './components/NavBarComponent.vue';
import ContentComponent from './components/ContentComponent.vue'
</script>

<template>
  <header>
    <NavBarComponent />
    <div class="main">
      <ContentComponent />
    </div>
  </header>

  <main>
  </main>
</template>

<style scoped>
.logo {
  display: block;
  margin: 0 auto 2rem;
}

</style>
