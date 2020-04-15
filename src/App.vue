<template>
  <div id="app">
    <Header></Header>
    <Hero></Hero>
  </div>
</template>

<script>

import { Header } from "./components/partials/Header";
import { Hero } from "./components/pages/Hero";

export default {
  name: "App",
  components: {
    Header,
    Hero,
  }
};

</script>
