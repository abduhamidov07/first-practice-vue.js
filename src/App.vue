<template>
  <div>
    <link rel="icon" href="./assets/logo.png" />
    <h1>{{ text }}</h1>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  data() {
    return {
      text: "Hello World!",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
}
div {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
h1 {
  font-size: 100px;
}
</style>
