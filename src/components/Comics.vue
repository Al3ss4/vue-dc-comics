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
  
  padding: 5px;
}

</style>