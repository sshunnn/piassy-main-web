<template>
  <body>
    <pcHeader />
    <img :src="image_src" />
    <h1>aaaaaaaaaa</h1>
    >
  </body>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      image_src: "@/assets/images/mainlogo.svg",
    };
  },
};
</script>
