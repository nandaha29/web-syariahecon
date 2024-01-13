<template>
  <h1>Halo ini dashboard</h1>
  <Jumbotron />
  <SectionSatu />
  <SectionDua />
</template>

<script>
import Jumbotron from "../components/Dashboard/Jumbotron.vue";
import SectionSatu from "../components/Dashboard/SectionSatu.vue";
import SectionDua from "../components/Dashboard/SectionDua.vue";

export default {
  components: {
    Jumbotron,
    SectionSatu,
    SectionDua,
  },
};
</script>
