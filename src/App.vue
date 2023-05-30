<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <section>
    <AppTitle />
  </section>
  <section>
    <AppHero />
  </section>
</template>

<style scoped></style>
