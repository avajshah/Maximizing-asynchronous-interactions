<template>
<v-form>
  <v-container class="module-metrics">
    <div class="module-metrics__container">
      <div class="text-center row font-weight-medium mr-auto ml-auto justify-center">
        Now that you have an idea for your project and what you are going to
        prototype, you have to prepare for Hack Day! This is a workshop to kick of
        the program once you are about to commit to a project.
      </div>
      <div class="col py-3 px-md-5 bordered col-example"></div>
      <p class="font-weight-bold text-md-h6 d-flex align-end">Team Name</p>
      <v-col cols="20" sm="20">
          <v-text-field
            outlined
          ></v-text-field>
        </v-col>
      <p class="font-weight-bold text-md-h6 d-flex align-end">Project Information</p>
      <v-col cols="20" sm="20">
          <v-textarea
            counter
            maxlength="500"
            hint="Talk about what your team has brainstormed/created so far."
            outlined
            full-width
            single-line
          ></v-textarea>
        </v-col>
        <!--Button have to fix-->
        <div class="module__header text-md-h6 text-sm-subtitle-1 d-flex align-end justify-center">
          <button @click="$router.push('Pros')">
          <input type="button" class="module__header-text" :value="moduleName">
          </button>
        </div>
    </div>
  </v-container>
</v-form>
</template>

<script lang="ts">
import Vue from 'vue';
import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModuleMetrics',
  apollo: {
  },
  data: () => ({
    moduleName: 'Continue to Pros',
  }),
});
</script>
