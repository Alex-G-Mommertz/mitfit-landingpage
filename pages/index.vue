<template>

  <v-row justify="center" align="center">
  
    <v-col cols="12" sm="12" md="12">  <Hero />
      </v-col>

      <v-col cols="12" sm="8" md="8">


      <v-container>
        
    <v-row no-gutters align="center">
<v-col cols="3" offset="3"><v-card align="center"
          class="py-8 px-4 ma-2 rounded-lg"
          color="primary"
          tile
        >
        <v-icon
  color="white"
  x-large
>mdi-account-group</v-icon>
          <p >Gesamtzahl:</p>
          <p class="font-weight-black" >40</p>
        </v-card></v-col>
<v-col cols="3"><v-card align="center"
          class="py-8 px-4 rounded-lg"
          color="primary"
          tile
        >
        <v-icon
  color="white"
  x-large
>mdi-calendar-clock</v-icon>
           <p >Teilnahmeschluss:</p>
           <p class="font-weight-black">31.12.2021</p>
        </v-card></v-col>
    </v-row>
  </v-container>
    </v-col>
  </v-row>
</template>

<script>

import Hero from "../components/Hero.vue"


export default {
  name: 'IndexPage',
  components: {
    Hero
  }
}
</script>

<style scoped>
.v-card p { color: #fff !important;}
</style>
