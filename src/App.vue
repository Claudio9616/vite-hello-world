<script>
import AppHero from './components/AppHero.vue'
import AppHeader from './components/AppHeader.vue'
export default {
  name: 'First app .Vue',
  components: {
    AppHeader,
    AppHero
  }
}
</script>
<template>
  <AppHeader />
  <AppHero />
</template>
<style></style>