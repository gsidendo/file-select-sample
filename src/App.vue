<template>
  <v-app>
    <v-content>
      <v-file-input
        show-size
        counter
        multiple
        label="File input"
      ></v-file-input>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "App",
  data: () => ({
    //
  })
});
</script>
