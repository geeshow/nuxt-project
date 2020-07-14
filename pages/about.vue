<template>
  <v-app>
    about
  </v-app>
</template>

<script>
export default {
  asyncData() {
    return {
      title: 'About',
    }
  },
  head() {
    return {
      title: 'About',
      script: [{ src: '/about.js' }],
    }
  },
}
</script>
