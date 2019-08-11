<template>
  <div>
    <h1>I am from user</h1>
    <!-- 205839fdc1d7d7a31dea3215b283c67249fb8be7 -->

    <input type="text" v-model="userId">
    <button @click="onLoadUser">Load User</button>
    <nuxt-child/>
  </div>
</template>
<script>
export default {
  data() {
    return {
      userId: ""
    };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/users/" + this.userId);
    }
  },
  layout: "users"
};
</script>
