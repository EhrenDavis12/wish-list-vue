<template>
  <v-app>
    <!-- <NavBar /> -->
    <v-container>
      <router-view />
    </v-container>
  </v-app>
</template>

<script>
// import NavBar from "./components/NavBar";

export default {
  name: "App",

  components: {
    // NavBar
  },

  data: () => ({
    //
  })
};
</script>
