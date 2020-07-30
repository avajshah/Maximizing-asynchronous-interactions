<template>
<v-form>
  <v-container class="module-instruct">
    <div class="module-instruct__container">
      <p class="text-center font-weight-bold text-md-h5">Steps</p>
      <div class="text-center row font-weight-medium mr-auto ml-auto justify-center">
        Get familiar with your employer and start connecting
      </div>
      <div class="col py-3 px-md-5 bordered col-example"></div>
      <!--Error Im getting if i type the whole thing is that it is too long-->
      <v-col cols="20" sm="100">
          <v-textarea
            clearable
            value="Get to know your employer by taking a look at their linkedin profile or other"
            outlined
            full-width
          ></v-textarea>
        </v-col>
        <v-col cols="20" sm="100">
          <v-textarea
            clearable
            value="Get to know your employer by taking a look at their linkedin profile or other"
            outlined
            full-width
          ></v-textarea>
        </v-col>
    </div>
  </v-container>
</v-form>
</template>

<script lang="ts">
import Vue from 'vue';
import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModuleInstruct',
  props: {
    readonly: {
      type: Boolean,
      default: false,
    },
  },
  apollo: {
  },
  data: () => ({
  }),
  methods: {
  },
});
</script>
