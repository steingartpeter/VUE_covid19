<template>
  <!-- Here only the HOME template is written to the HTML site -->
  <div class="home">
    <main-page />
  </div>
</template>

<script>
import MainPage from "../components/MainPage/MainPage.vue";
// @ is an alias to /src
// Jelenleg semmi érdekes...
export default {
  name: "Home",
  components: { MainPage },
};
</script>
