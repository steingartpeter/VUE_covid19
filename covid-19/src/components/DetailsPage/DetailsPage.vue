<template>
  <div class="DetailsPage">
    <Header />
    <pre v-text="$attrs"></pre>
  </div>
</template>

<script>
import Header from "../Header.vue";
export default {
  components: { Header },
  props: {},
};
</script>
