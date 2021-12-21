<template>
  <v-parallax
    dark
    src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        <h1 class="text-h4 font-weight-thin mb-4">
          Vuetify
        </h1>
        <h4 class="subheading">
          Build your application today!
        </h4>
              <v-card>
        <v-card-title class="headline d-flex">
          <h2>40 Personen gesucht für unser</h2>
           <h1 class="text-center">5 WOCHEN-ABNEHMPROGRAMM!</h1>
        </v-card-title>
      </v-card>
      </v-col>
    </v-row>
  </v-parallax>
</template>

<script>
  export default {
    name: 'Hero'
  }
</script>