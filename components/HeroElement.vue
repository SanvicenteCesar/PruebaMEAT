<template>
  <section class="hero">
    <h1 class="hero__heading">El secreto de tu cocina</h1>
    <img src="../assets/images/brush.png" alt="Brush" class="hero__brocha" />
  </section>
</template>

<script>
export default {
  name: "HeroElement",
  data() {
    return {
      title: "",
      message: ``,
      primaryButtonText: "",
      secondaryButtonText: "",
      media: "",
    };
  },
};
</script>

<style lang="scss" scoped>
.hero {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-inline: 14.375rem;
  background-image: url("../assets/images/hero.png");
  background-size: cover;

  &__heading {
    position: relative;
    max-width: 32rem;
    font-family: "Caveat";
    font-weight: 700;
    font-size: 120px;
    line-height: 100px;
    color: #3f454a;
    z-index: 1;
  }

  &__brocha {
    position: absolute;
    bottom: 16.9rem;
    left: -26rem;
    z-index: 0;
    width: auto;
    height: 15rem;
    // background-image: url("../assets/images/brush.png");
  }
}
</style>