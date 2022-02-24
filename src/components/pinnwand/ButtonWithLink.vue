<template>
  <v-btn rounded block color="primary" size="large" :href="link" target="_blank">
    <v-icon left> mdi-movie-open-play</v-icon>
    {{ buttonText }}
  </v-btn>
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