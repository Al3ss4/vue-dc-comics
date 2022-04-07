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

  
  img{
   display: block;
   width: 100%;
   padding: 20px;
        &:hover
        {
            transform: scale(1.1);
            cursor: pointer;
        }
  }
  h2{
    text-transform: uppercase;
    font-size: 0.9rem;
    padding: 0 20px;
  
  }
}

</style>