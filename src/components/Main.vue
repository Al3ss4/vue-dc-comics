<template>
  <main>
    <div class="container">
      <Comics v-for="(item, index) in series" :key="index" :element="item" />
    </div>
    <div class="text-container">
      <a href="#">
        <h3 class="txt">LOAD MORE</h3>
      </a>
    </div>
  </main>
</template>

<script>
import Comics from "@/components/Comics.vue";
import Series from "@/data/dc-comics.js";

export default {
  name: "MainComponent",
  components: {
    Comics,
  },
  data() {
    return {
      series: Series,
    };
  },
};
</script>

<style lang="scss" scoped >
$bg-main: #1c1c1c;
$color-main: white;

main {
  background-color: $bg-main;
  color: $color-main;
  margin: 0px 0px;
  padding: 30px 90px;

  .container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-bottom: 17px;
  }
  .text-container {
    display: flex;
    justify-content: center;
    a{
       text-decoration-line: none;
    }
    .txt {
      color: white;
      background-color: #0282f9;
      padding: 10px 20px;
    }
  }
}
</style>