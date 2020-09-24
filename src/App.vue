<template>
  <div id="app">
    <img
      src="https://i.pinimg.com/originals/2a/02/d6/2a02d695bfc48aa79b17a436a1a121b2.gif"
      class=""
      width="17%"
    />
    <p></p>
    <pinterest />
  </div>
</template>
<script>
import Pinterest from "./components/Pinterest.vue";
export default {
  name: "App",
  components: {
    Pinterest,
  },
};
</script>
<style>
#app {
  background-image: url(https://i.pinimg.com/originals/35/f2/a5/35f2a54da02f0cefb0bc6e13b6c8f310.jpg);
  background-size: mode;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #3a0414;
  margin-top: 60px;
}
</style>