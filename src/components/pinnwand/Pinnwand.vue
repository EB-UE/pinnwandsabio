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

    <v-row class="bg-primarys">
      <v-col cols="4">
        <v-btn
          rounded
          block
          color="primary"
          to="https://eb.sabio.de/web/#!/fullscreen/_id/1644246169/text/_id/520f21a91e074501b866b43f42c8d57d"
        >
          <v-icon left> mdi-movie-open-play</v-icon> Wie bediene ich die
          Suche?</v-btn
        >
      </v-col>
      <v-col cols="4">
        <v-btn
          rounded
          block
          color="primary"
          to="https://eb.sabio.de/web/#!/fullscreen/_id/1644246199/text/_id/0607fe0c8034467dafa3e1b8af1875ae"
        >
          <v-icon left> mdi-movie-open-play</v-icon>Wie Kann ich die Ansichten
          steuern?</v-btn
        >
      </v-col>
      <v-col cols="4">
        <v-btn
          rounded
          block
          color="primary"
          to="https://eb.sabio.de/web/#!/fullscreen/_id/1644246223/text/_id/d10b2c41ac7e48ea9a6a796dd79895fd"
        >
          <v-icon left> mdi-movie-open-play</v-icon>Wie kann ich einen Vorschlag
          unterbreiten?</v-btn
        >
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Mooswand_mit_Kacheln from "../../assets/pinnwand/Mooswand_mit_Kacheln.png";

export default {
  data: function () {
    return {
      hintergrundBild: Mooswand_mit_Kacheln,
    };
  },
};
</script>

<style>
</style>