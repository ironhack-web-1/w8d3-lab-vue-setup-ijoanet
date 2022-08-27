<template>
  <div id="about">
    <p>This is the 'aboutMe' content</p>
    <p>{{ aboutMe }}</p>
    <p>And this is Jesus just dacing</p>
    <img src="https://i.pinimg.com/originals/3c/bc/58/3cbc5852b03e549f6ff4d14c80031349.gif">
  </div>
</template>

<script>
export default {
  name: 'AboutComponent',
  props: {
    aboutMe: {
      type: String,
      default: '😢There\'s nothing to talk about!😢',
    },
  },
};

</script>

<style scoped>
#about {
    width: 70%;
    margin: auto;
}
p:nth-child(1), p:nth-child(3) {
  font-weight: 700;
}
p:nth-child(2) {
    text-align: justify;
}
</style>
