<template>
  <div class="header">
    <router-link to="/" class="logo">
      <img src="../assets/logo.svg" alt="Lien vers la page d'accueil" />
    </router-link>
    <h1>Mes films</h1>
    <div class="nav">
      <router-link to="/bookmarks">Favoris</router-link>
      <router-link to="/about">A propos</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
.header {
  display: flex;
  align-items: center;
  background-color: hsl(260, 71%, 62%);
  padding: 1rem;
}
.logo {
  width: 5rem;
  margin: 1rem 1rem 1rem 0;
}
.nav {
  margin-left: auto;
}
.nav > a {
  color: white;
  cursor: pointer;
  font-size: 1.6rem;
}
.nav > a:not(first-child) {
  margin-left: 1rem;
}

h1 {
  font-family: "Raleway", sans-serif;
  font-size: 2rem;
  color: #fff;
}
</style>