<template>
  <header class="main-header">
      <nuxt-link to="/" class="list-items">Locations</nuxt-link>
      <nuxt-link to="/about" class="list-items">About me</nuxt-link>
  </header>
</template>

<style lang="scss">
.main-header {
  height: 10vh;
  background: grey;
  width: 100vw;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  a {
    text-decoration: none;
    color: #ffffff;
    font-weight: 800;
  }
  .list-items {
    margin: 0px 20px;
    list-style-type: none;
    text-decoration: none;
  }
}
</style>
