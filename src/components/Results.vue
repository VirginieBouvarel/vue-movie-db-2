<template>
  <section class="results">
    <h2 class="sr-only">Résultats</h2>
    <ul class="cards"></ul>
  </section>
</template>

<script>
export default {
  name: "Results",
};
</script>

<style lang="scss" scoped>
.results {
  padding: 2rem 1rem;
}
.cards {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-around;
}
</style>