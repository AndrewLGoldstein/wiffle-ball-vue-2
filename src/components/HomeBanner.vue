<template>
  <v-container fluid id="banner">
    <v-row mb-5 class="text-left">
      <v-col md="11" offset-md="1">
        <v-icon dark x-large class="logo">mdi-baseball-diamond-outline</v-icon>
      </v-col>
    </v-row>
    <v-row class="text-left"> </v-row>
  </v-container>
</template>

<script>
export default {}
</script>

<style>
#banner {
  background-image: url('../assets/background.jpeg');
  height: calc(100vh - 64px);
  overflow-y: hidden;
  background-position: bottom;
  background-repeat: no-repeat;
  background-size: cover;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}

.logo {
  border-radius: 100%;
  border: solid 2px #ffffff9a;
  cursor: default;
  display: inline-block;
  font-size: 2em;
  height: 2.25em;
  line-height: 2.25em;
  text-align: center;
  width: 2.25em;
}
</style>
