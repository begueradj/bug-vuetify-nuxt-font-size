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
        <main-component />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import MainComponent from '@/components/MainComponent.vue'
export default {
  components: {
    MainComponent
  }
}
</script>
