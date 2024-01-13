<template>
  <Navbar />

  <!-- router yang akses view -->
  <RouterView />
</template>

<script>
import Navbar from "./components/Navbar.vue";

export default {
  components: {
    Navbar,
  },
};
</script>
