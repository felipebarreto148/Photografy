<template>
  <v-app>
    <v-app-bar app flat color="white">
      <Header />
    </v-app-bar>
    <v-main>
      <Hero />
      <Gallery />
      <LatestPost />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import Hero from "./components/Hero";
import Gallery from "./components/Gallery";
import LatestPost from "./components/LatestPost";

export default {
  name: "App",

  components: {
    Header,
    Hero,
    Gallery,
    LatestPost,
  },

  data: () => ({
    //
  }),
};
</script>
