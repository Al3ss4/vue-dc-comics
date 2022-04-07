<template>
  <div class="container">
    <img :src="element.thumb" />
    <h2>{{ element.series }}</h2>
  </div>
</template>

<script>
export default {
  name: "Comics-series",
  props: ["element"],
};
</script>

<style lang="scss" scoped>
.container {
  display: flex;
  flex-direction: column;
  width: calc(100% / 6);

  img {
    padding: 20px;
    object-fit: cover;
    object-position: 0% 0%;
    &:hover {
      transform: scale(1.1);
      cursor: pointer;
    }
  }
  h2 {
    text-transform: uppercase;
    font-size: 0.9rem;
    padding: 0 20px;
  }
}
</style>