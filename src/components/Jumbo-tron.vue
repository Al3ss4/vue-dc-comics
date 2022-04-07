<template>
  <div class="jumbo-space">
    <a href="#">
      <h2 class="series">CURRENT SERIES</h2>
    </a>
  </div>
</template>


<script>
export default {
  name: "Jumbo-tron",
};
</script>


<style lang="scss" scoped>
.jumbo-space {
  height: 400px;
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: cover;
  position: relative;
  .series {
    color: white;
    padding: 10px 17px;
    background-color: #0282f9;
    width: 13%;
    position: absolute;
    bottom: -20px;
    left: 165px;
    z-index: 999;
  }
}
</style>