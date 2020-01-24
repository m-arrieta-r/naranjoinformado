<template>
  <div class="container">
    <Logo />
    <Candidates />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Candidates from '~/components/Candidates/index.vue'

export default {
  components: {
    Logo,
    Candidates
  }
}
</script>

<style>
body {
  background: #15202b;
}

.container {
  margin: 10px;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
