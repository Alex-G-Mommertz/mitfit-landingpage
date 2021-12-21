<template>
  <v-app dark>

    <v-app-bar fixed>
      <v-row justify="center" align="center">
      <v-col cols="12" sm="12" md="8" class="d-flex justify-space-between" flat tile>
      <VuetifyLogo />
      <PopForm />
      </v-col>
      </v-row>
    </v-app-bar>
    <v-main>
      <v-container
      fluid>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>

import PopForm from "../components/form.vue"


export default {
  name: 'DefaultLayout',
  components: {
    PopForm
 } 
}
</script>


