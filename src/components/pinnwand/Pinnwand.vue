<template>
  <v-container>
    <v-row>
      <v-col>
        <span class="text-h2 text-primary"
          >Herzlich Willkommen im Wissensmanagement der EB-KS</span
        >
      </v-col>
    </v-row>

    <v-row>
      <v-col>
        <v-img :src="hintergrundBild"></v-img>
      </v-col>
    </v-row>

   <v-row>
      <v-col>
        <span class="text-h5 text-primary"
          >Wie kann ich ...</span
        >
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="4">
        <button-with-link
          buttonText="die Suche benutzen?"
          link="https://eb.sabio.de/web/#!/fullscreen/_id/1644246169/text/_id/520f21a91e074501b866b43f42c8d57d"
        ></button-with-link>
      </v-col>
      <v-col cols="4">
        <button-with-link
          buttonText="die Ansichten steuern?"
          link="https://eb.sabio.de/web/#!/fullscreen/_id/1644246199/text/_id/0607fe0c8034467dafa3e1b8af1875ae"
        ></button-with-link>
      </v-col>
      <v-col cols="4">
        <button-with-link
          buttonText="einen Vorschlag hinzufügen?"
          link="https://eb.sabio.de/web/#!/fullscreen/_id/1644246223/text/_id/d10b2c41ac7e48ea9a6a796dd79895fd"
        ></button-with-link>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Mooswand_mit_Kacheln from "../../assets/pinnwand/Mooswand_mit_Kacheln.png";
import ButtonWithLink from "./ButtonWithLink.vue";

export default {
  components: { ButtonWithLink },
  data: function () {
    return {
      hintergrundBild: Mooswand_mit_Kacheln,
    };
  },
};
</script>

<style>
</style>