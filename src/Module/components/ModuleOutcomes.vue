<!--settings-->
<template>
  <v-container class="module-settings">
    <div class="module-settings__container">
      <div class="text-center row font-weight-bold mr-auto ml-auto justify-center">
        Minimum amount of connections and follows made with laison media.
      </div>
      <!--Dropdown-->
      <div class="text-center row justify-center">
      <v-col class="d-flex" cols="6">
        <v-select
          :items="items"
          label="Connections"
        ></v-select>
      </v-col>
      </div>
        <div class="text-center row font-weight-bold justify-center">
          Desired amount of connections and follows suggested by laison
        </div>
      <!--Dropdown-->
      <div class="text-center row justify-center">
      <v-col class="d-flex" cols="6">
        <v-select
          :items="items"
          label="Connections"
        ></v-select>
      </v-col>
      </div>
    </div>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue';
// import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModuleSettings',
  apollo: {
  },
  data: () => ({
    items: ['1', '2', '3', '4'],
  }),
});
</script>
