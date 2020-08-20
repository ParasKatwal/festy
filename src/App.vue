<template>
  <v-app>
    <NavBar />
    <router-view :key="$route.fullPath" />
  </v-app>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar
  },
  data: () => ({
    //
  })
};
</script>
