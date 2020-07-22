<!--  Cons -->
<template>
  <v-container class="module-cons">
    <div class="module-cons__container">
      <div class="text-center row font-weight-medium mr-auto ml-auto justify-center">
        Now that you have filled out the Pros for your project a list of Cons
        or obstacles that you might encounter throughout this project
      </div>
      <div class="col py-3 px-md-5 bordered col-example"></div>
      <p class="font-weight-bold text-md-h6 d-flex align-end">List of Cons</p>
      <v-col cols="20" sm="20">
          <v-textarea
            hint="It is preferable to create a bullet point list"
            outlined
            full-width
            single-line
          ></v-textarea>
        </v-col>
    </div>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue';
// import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModuleCons',
  apollo: {
  },
  data: () => ({
  }),
});
</script>
