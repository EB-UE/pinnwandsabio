<template>
  <v-app>
    <v-main>
      <Pinnwand></Pinnwand>
    </v-main>
  </v-app>
</template>

<script>
import Pinnwand from "./components/pinnwand/Pinnwand.vue";

export default {
  name: "App",

  components: {
    Pinnwand,
  },

  data: () => ({
    //
  }),
};
</script>
