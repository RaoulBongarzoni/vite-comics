<script>
import my_nav from "./components/Nav.vue"
import my_main from "./components/MainContent.vue"
export default {

  components: {

    my_nav,
    my_main
  }

}
</script>



<template>
  <my_nav />

  <my_main />
</template>

<style>
.container {
  height: 100%;
  max-width: 900px;
  display: flex;
  justify-content: space-between;

  margin: 0 auto;
  align-items: center;

}
</style>