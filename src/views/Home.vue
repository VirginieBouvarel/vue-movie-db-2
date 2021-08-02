<template>
  <div class="home">
    <SearchForm />
    <Results />
  </div>
</template>

<script>
// @ is an alias to /src
import SearchForm from "@/components/SearchForm.vue";
import Results from "@/components/Results.vue";

export default {
  name: "Home",
  components: {
    SearchForm,
    Results,
  },
};
</script>
