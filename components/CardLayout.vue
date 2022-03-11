<template>
  <div class="card card--container">
    <aside>a</aside>
    <div>ab</div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.card {
  min-height: 100vh;

  &--container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }
}
</style>