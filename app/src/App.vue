<script>
import TheNavbar from './components/TheNavbar.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  components: {
    TheNavbar,
    TheFooter,
  },
  data: () => ({
    tagline: 'Track the food what you want to eat'
  }),
}
</script>

<template>
  <TheNavbar :tagline="tagline" />
  <RouterView />
  <TheFooter />
</template>

<style></style>
