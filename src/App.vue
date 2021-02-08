<template>
  <div id="app">
    <div class="navbar">
      <Books />
    </div>
  </div>
</template>

<script>
import Books from "./components/Books.vue";

export default {
  name: "app",
  components: {
    Books
  }
};
</script>

<style lang="scss">
@import "./styles/main.scss";

.navbar {
  background-color: orange;
  width: 100%;
  height: 96px;
  position: absolute;
  z-index: 0;
}

</style>
