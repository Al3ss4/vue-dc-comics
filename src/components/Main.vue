<template>
  <main>
    <div>
      <div class="container">
        <Comics
          v-for="(item, index) in series"
          :key="index"
          :element="item"
        />
      </div>
      <a href="#">
        <h3>LOAD MORE</h3>
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
      series: Series
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
  font-size: 30px;
  .container{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }
}
</style>