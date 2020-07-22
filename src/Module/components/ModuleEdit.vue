<!-- Future Ideas -->
<template>
<v-container class="module-futureideas">
  <div class="module-futureideas__container">
    <div class="text-center row font-weight-medium mr-auto ml-auto justify-center">
        One last step! Write down some future ideas (long run goals) you and your team are planning
        to achieve and some ways you are planning to meet them
      </div>
        <div class="col py-3 px-md-5 bordered col-example"></div>
      <p class="font-weight-bold text-md-h6 d-flex align-end">Future Ideas or Thoughts</p>
  </div>
  <v-col cols="20" sm="20">
          <v-textarea
            hint="Don't worry if you aren't sure just do your best!"
            outlined
            full-width
            single-line
          ></v-textarea>
        </v-col>
</v-container>
</template>

<script lang="ts">
import Vue from 'vue';
// import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModuleFutureIdeas',
  apollo: {
  },
  data: () => ({
  }),
});
</script>
