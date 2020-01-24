<template>
  <div class="nuxt-logo">
    <img class="nuxt-logo__img" src="~/static/logo-small.png" alt="logo">
  </div>
</template>

<style lang="scss">
.nuxt-logo {
  display: flex;
  animation: 1s appear;

  &__img {
    width: 100px;
    margin: auto;
  }
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
