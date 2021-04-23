<template>
  <v-container>
    <div id="msg">hello, world!</div>
    <div>{{ name }}</div>
  </v-container>
</template>
<script>
  import Vue from 'vue';

  export default {
      name: "Main",
      data() {
          return {
              message: "Hello, world!",
              name: "Bob",
          }
      }
  }
</script>
<style scoped>
  #msg {
    font-size: 24px;
    color: lightgreen;
  }
</style>