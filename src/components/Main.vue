<template>
  <main>
    <main>--&gt; Content gose here &lt;--</main>
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
  background-image: $bg-main;
  color: $color-main;
  margin: 30px 70px;
  display: flex;
  align-items: flex-start;
  font-size: 20px;
}
</style>