<template>
  <v-app>
    <v-app-bar app color="#111111" dark>
      <div class="d-flex align-center" style="padding-right: 20px; color:#d0d0d0; ">Threat Hunting</div>
        <div class="d-flex align-center" style="padding-right: 20px; color:#d0d0d0;">Protocols</div>
      <div class="d-flex align-center" style="padding-right: 20px; color:#d0d0d0;">Write plugins</div>
      <div class="d-flex align-center" style="padding-right: 20px; color:#d0d0d0;">Tutorial</div>
      <v-spacer></v-spacer>
      <div class="d-flex align-center" style="padding-right: 20px; color:#d0d0d0;">Log in</div>
    </v-app-bar>

    <v-content style="background-color: #111111;">
      <Portal />
    </v-content>
  </v-app>
</template>

<script>
import Portal from "./components/Portal";

export default {
  name: "App",

  components: {
    Portal
  },

  data: () => ({
    //
  })
};
</script>
