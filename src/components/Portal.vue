<template>
  <v-container>
    <v-row justify="center" >
      <v-col cols="12" sm="1" class="d-flex justify-center">
        <h1 style="color:#488ed2; font-size:50px; font-weight: 400">NETLOG</h1>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="3" class="d-flex justify-center">
        <center><p style="color:#d0d0d0">An extensible framework for forensic network analysts. Customize Netlog to find what you are looking for.</p></center>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="4">
        <center>
          <div class="mycontainer"></div>
        </center>
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="4">
        <center>
          <br>
          <v-btn
            rounded
            style="background-color: #111111; color: #488ed2; border: 2pt solid #488ed2"
          >Analyze pcap file</v-btn>
        </center>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Portal",
  data: () => ({})
};
</script>
<style scoped lang="scss">
.mycontainer {
  z-index: 2;
  background-image: radial-gradient(closest-side, #11111100 70%, #111111ff 100%),
    url("~@/assets/glassbits.jpg"); /* W3C */
  height: 273px;
  width: 390px;
}
</style>
