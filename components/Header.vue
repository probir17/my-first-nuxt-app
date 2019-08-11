<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/products">Products</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
.header {
  width: 100%;
  height: 60%;
  display: flex;
  justify-content: content;
  align-items: center;
  background-color: burlywood;
}

.nav-items {
  list-style: none;
  padding: 0;
  margin: 0;
  display: none;
  justify-content: space-around;
  align-items: center;
  width: 80%;
}
</style>

