<template>
  <video-player></video-player>
</template>

<script>
import VideoPlayer from "./components/VideoPlayer.vue";
export default {
  name: "app",
  components: {
    VideoPlayer
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
