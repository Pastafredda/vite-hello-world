<script>
import AppTitle from './components/AppTitle.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  components: {
    AppTitle,
    Jumbotron
  }
}
</script>

<template>
  <section>
    <AppTitle />
  </section>
  <section>
    <Jumbotron />
  </section>
</template>

<style scoped></style>
