<template>
  <div class="navBar">
    <v-container>
      <div class="d-flex justify-space-between">
        <h1>LOGO</h1>
        <v-btn target="_blank" text>
          <v-icon>mdi-open-in-new</v-icon>
          <span class="mr-2">המועדפים שלי</span>
        </v-btn>
      </div>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style lang="scss" scoped>
</style>