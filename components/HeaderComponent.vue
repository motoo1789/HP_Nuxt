<template>
    <div>
        <v-app-bar :clipped-left="true" app>
            <v-toolbar-title>{{ title }}</v-toolbar-title>
            <v-spacer />
        </v-app-bar>     
    </div>
</template>
  
<script>
  export default {
  
      data() {
          return {
              title: "Motoo Lab",
              clipped: true,
          }
      },
      computed: {
      }
  }
  </script>
  
  <style>
  
  </style>