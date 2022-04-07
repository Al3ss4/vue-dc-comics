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

.container{
  display: flex;
  flex-direction: column;
  width: calc(100% / 6);
  padding: 10px;
  text-align: center;
  img{
    width: 100%;
  }
  h2{
    font-size: 1.4rem;
  }
}

</style>