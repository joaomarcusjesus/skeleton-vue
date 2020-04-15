<template>
  <header class="header">
    <div class="container">
      <Brand></Brand>
      <Nav></Nav>
    </div>
  </header>
</template>

<script>

import { Nav } from "./Nav";
import { Brand } from "./Brand";

export default {
  name: "Header",
  components: {
    Nav,
    Brand,
  }
};

</script>

<style class="scss">

.header {
  position: fixed;
  background: blue;
  width: 100%;
  z-index: 30;
  top: 0;
  padding: 25px;
}

</style>
