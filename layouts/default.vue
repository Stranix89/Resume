<template>
  <v-app dark>
    <div class="navigation">
      <v-container>
        <NavigationSite />
      </v-container>
    </div>
    <v-main>
      <Nuxt />
    </v-main>
    <!--<v-footer app max-height="58px">
      <span>&copy; {{ new Date().getFullYear() }}</span>
      <MyContacts />
    </v-footer>-->
  </v-app>
</template>

<script>

</script>

<style scoped>
.v-footer {
  background-color: #04ed93;
}
</style>
