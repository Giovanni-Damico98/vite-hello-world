<script>
import AppJumbotron from "./components/AppJumbotron.vue";
import AppTitle from "./components/AppTitle.vue";

AppTitle;
export default {
  components: { AppTitle, AppJumbotron },
  data() {
    return {};
  },
};
</script>

<template>
  <AppTitle />
  <AppJumbotron />
</template>

<style scoped></style>
