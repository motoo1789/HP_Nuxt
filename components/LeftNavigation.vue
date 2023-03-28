<template>

    <v-navigation-drawer
      mobile-breakpoint="960"
      app 
      :clipped="true"

    >
      <v-list>
        <v-list-item v-for="sidelist in sidelists" 
          :key="sidelist.titleJP" 
          prepend-icon="subtitle.icon"
          @click="changeComponent(sidelist.titleENG)"
        >
          {{ sidelist.titleJP }}
        </v-list-item> 
      </v-list>
    </v-navigation-drawer>
    

</template>

<script>
export default {
    data: () => ({
    drawer: null,
    sidelists: [
      {titleJP: "ホーム", titleENG: "Home", path: "/",  icon:"mdi-home-outline"},
      {titleJP: "プロフィール", titleENG: "Profile", path: "/profile", icon:"mdi-account-outline"},
    ]
  }),
}
</script>

<style>

</style>