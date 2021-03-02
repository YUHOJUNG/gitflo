<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to git" />
    <div class="test">1줄 추가해서 style엘리먼트도 밀렸을 경우</div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 15px; /* 한 번 더 추가 */
  background-color: skyblue; /* 개행하지 않고 중간에 추가했을 경우 */
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
