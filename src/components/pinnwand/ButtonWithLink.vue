<template>
  <a target="_blank" rel="noopener noreferrer" :href="link">
    <v-btn rounded block color="primary">
      <v-icon left> mdi-movie-open-play</v-icon>
      {{ buttonText }}</v-btn
    ></a
  >
</template>

<script>
export default {
  props: {
    link: String,
    buttonText: String,
  },
};
</script>

<style>
</style>