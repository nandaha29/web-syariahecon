<template>
  <h1>Halo ini dashboard</h1>
  <Jumbotron />
  <SectionSatu />
  <SectionDua />
  <SectionTiga />
  <SectionEmpat />
</template>

<script>
import Jumbotron from "../components/Dashboard/Jumbotron.vue";
import SectionSatu from "../components/Dashboard/SectionSatu.vue";
import SectionDua from "../components/Dashboard/SectionDua.vue";
import SectionTiga from "../components/Dashboard/SectionTiga.vue";
import SectionEmpat from "../components/Dashboard/SectionEmpat.vue";

export default {
  components: {
    Jumbotron,
    SectionSatu,
    SectionDua,
    SectionTiga,
    SectionEmpat,
  },
};
</script>
