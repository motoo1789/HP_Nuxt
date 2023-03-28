<template>
    <div>
        <v-app-bar :clipped-left="true" app>
            <v-spacer />
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
  .border-b {
    border: 1px red;
  }
  </style>