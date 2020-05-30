<template>
  <v-app>
    <v-app-bar app color="primary" dark fixed style="background-color: #6d2b70 !important;">
      <div class="d-flex align-center">
        <v-img
          alt="Logo"
          class="mr-2"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="200"
        />
      </div>
      <v-spacer></v-spacer>
      <Navbar />
    </v-app-bar>
    <v-row style="margin-top: 64px !important;">
      <Carousel />
      <v-container fluid>
        <Gallery />
        <StayInTouch />
      </v-container>
    </v-row>
  </v-app>
</template>

<script>
import Navbar from "@/components/Navbar/Navbar";
import Carousel from "@/components/Carousel/Carousel";
import Gallery from "@/components/Gallery/Gallery";
import StayInTouch from "@/components/StayInTouch/StayInTouch";
export default {
  name: "App",
  components: {
    Navbar,
    Carousel,
    Gallery,
    StayInTouch
  },
  data: () => ({})
};
</script>