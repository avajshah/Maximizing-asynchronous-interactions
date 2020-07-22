<!--  Pros -->
<template>
<!--  TODO: make the inputs into actual components -->
  <v-container class="module-pros">
    <div class="module-pros__container">
    </div>
  </v-container>
</template>

<script lang="ts">
import Vue from 'vue';
import gql from 'graphql-tag';

export default Vue.extend({
  name: 'ModulePros',
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
