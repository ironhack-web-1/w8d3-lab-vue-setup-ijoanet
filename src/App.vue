<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="./assets/logo.png"
    >
    <AboutComponent
      about-me="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate sodales metus in accumsan. Suspendisse sagittis orci in enim consequat vulputate. Sed porta pretium nulla at pretium. Vivamus volutpat congue velit et molestie. Pellentesque id viverre mauris. Etiam est mauris, sagittis sit amet pharetra sit amet, ullamcorper sit amet nisi. Duis vestibulum magna sapien, a tempor massa dictum sed. Duis non aliquam odio. Fusce neque quam, dignissim a diam sed, semper interdum ante. Nullam viverra nulla efficitur, sagittis nunc a, ornare massa. Praesent blandit volutpat est a varius."
    />
  </div>
</template>

<script>
import AboutComponent from './components/AboutComponent.vue';

export default {
  name: 'App',
  components: {
    AboutComponent,
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
</style>
