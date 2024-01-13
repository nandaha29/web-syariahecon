<template>
  <h1>Halo ini dashboard</h1>
  <Jumbotron />
  <SectionSatu />
</template>

<script>
import Jumbotron from "../components/Dashboard/Jumbotron.vue";
import SectionSatu from "../components/Dashboard/SectionSatu.vue";

export default {
  components: {
    Jumbotron,
    SectionSatu,
  },
};
</script>
