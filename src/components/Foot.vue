<template>
  <footer>
    <a :href="this.$store.state.endpoint.replace('/wp-json/wp/v2', '')">Phonandroid.com</a>
  </footer>
</template>

<script>
  export default {
    name: 'Foot',
    link: ''
  }
</script>

<style scoped lang="scss">
  footer {
    text-align: center;
    padding: 1rem;
    background: $gray--light;
  }

  a {
    font-weight: bold;
  }
</style>
