<template>
    <v-footer>
        <v-card
          elevation="0"
          rounded="0"
          width="100%"
          class="bg-grey text-center"
        >  
          <v-card-text class="text-black">
            @ {{ new Date().getFullYear() }} —
            <strong>Warung Kopi Asoy</strong>
          </v-card-text>
        </v-card>
      </v-footer>
  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style>
  .v-footer {
    padding: 8px 0 !important;
  }
  </style>