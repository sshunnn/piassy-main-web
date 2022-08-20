<template>
  <div>
    <img v-bind:src="image_src" />
    <h1>aaaaaaa</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      image_src: "mainlogo.svg",
    };
  },
};
</script>
<style>
img {
  display: block;
  margin: 15% auto;
}
</style>
