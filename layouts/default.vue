<template>
  <div>
    <v-card color="grey lighten-4" flat height="200px" tile>
      <v-toolbar prominent extended>
        <v-app-bar-nav-icon></v-app-bar-nav-icon>

        <v-toolbar-title>My practice project</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn text>
          <n-link to="/">Home</n-link>
        </v-btn>

        <v-btn text>
          <n-link to="/about">About</n-link>
        </v-btn>

        <v-btn text>
          <n-link to="/inspire">Inspire</n-link>
        </v-btn>
      </v-toolbar>
    </v-card>
    <nuxt />
  </div>
</template>
<script>
export default {}
</script>
