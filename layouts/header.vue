<template>
  <header class="main-header">
      <nuxt-link to="/"><li class="list-items">Locations</li></nuxt-link>
      <!-- <nuxt-link to="/about"><li class="list-items">About me</li></nuxt-link> -->
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
    .list-items {
      margin: 0px 20px;
      list-style-type: none;
      text-decoration: none;
    }
  }
}
</style>
