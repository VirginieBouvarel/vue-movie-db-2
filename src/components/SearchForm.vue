<template>
  <section class="search">
    <form action="" class="form">
      <input type="search" class="input" />
      <button type="submit" class="btn">Rechercher</button>
    </form>
  </section>
</template>

<script>
export default {
  name: "SearchForm",
};
</script>

<style lang="scss" scoped>
.form {
  padding: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.input {
  border: none;
  border: 1px solid silver;
  border-radius: 3px;
  padding: 0.5rem;
  width: 75%;
}
.btn {
  border: none;
  background-color: hsl(260, 71%, 62%);
  color: hsl(0, 0%, 100%);
  padding: 1rem;
  border-radius: 3px;
  margin-top: 1rem;
}
</style>