<template>
  <v-app dark>

    <v-app-bar :clipped-left="clipped" fixed app>
      <v-toolbar-title v-text="title" />
      <v-spacer />
      <PopForm />
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
