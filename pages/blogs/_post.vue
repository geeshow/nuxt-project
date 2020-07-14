<template>
  <div>
    <h1>{{ slog.post }}</h1>
  </div>
</template>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.post)
  },
  data() {
    return {
      slog: this.$route.params,
    }
  },
  created() {
    /* eslint-disable no-console */
    console.log(this.$route.params)
  },
}
</script>

<style></style>
