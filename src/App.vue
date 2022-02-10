<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld /> -->
      <Pinnwand></Pinnwand>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Pinnwand from "./components/pinnwand/Pinnwand.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    Pinnwand,
  },

  data: () => ({
    //
  }),
};
</script>
