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
  padding: 5px;
  
  img{
    width: 100%;
    margin-bottom: 15px;
  }
  h2{
    text-transform: uppercase;
    font-size: 0.9rem;
  }
}

</style>