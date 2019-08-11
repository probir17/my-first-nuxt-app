<template>
  <div>
    <h1>I am product page</h1>
    <button @click="onLoadProductPage1">Product page 1</button>
    <button @click="onLoadProductPage2">Product page 2</button>
  </div>
</template>

<script>
export default {
  methods: {
    onLoadProductPage1() {
      this.$router.push("/products/1");
    },
    onLoadProductPage2() {
      this.$router.push("/products/2");
    }
  }
};
</script>
