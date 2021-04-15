<template>
  <div class="home">
    <Geoanalytics  />
  </div>
</template>

<script>
// @ is an alias to /src
import Geoanalytics from "@/components/Geoanalytics.vue";

export default {
  name: "Home",
  components: {
    Geoanalytics,
  },
};
</script>
