<template>
  <div class="footer">
    <p class="copyright">Réalisé par virginieBouvarel&#169;2021</p>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.footer {
  background-color: hsl(260, 71%, 62%);
  position: fixed;
  bottom: 0;
  width: 100%;
  min-height: 10rem;
  color: hsl(0, 0%, 100%);
  text-align: center;
}

.copyright {
  margin: 3rem;
  font-size: 1.1rem;
}
</style>