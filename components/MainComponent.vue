<template>
  <v-container
    grid-list-md
    text-xs-center
    fill-height
  >
    <v-layout
      row
      wrap
      align-center
    >
      <v-flex
        xs12
      >
        <sub-component />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import SubComponent from '@/components/SubComponent.vue'

export default {
  name: 'MainComponent',
  components: {
    SubComponent
  }
}
</script>
