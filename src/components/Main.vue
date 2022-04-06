<template>
  <main>
    <main>--&gt; Content goes here &lt;--</main>
  </main>
</template>

<script>
export default {
  name: "MainComponent",
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
  display: flex;
  align-items: flex-start;
  font-size: 30px;
  
}
</style>