<script setup>
import mainBanner from '../assets/images/main-banner.png'
import wordcloud from '../assets/images/wordcloud-infomama.webp'
</script>

<template>
  <v-parallax :src="mainBanner" height="75vh">
    <v-row no-gutters class="h-100 align-md-end justify-center justify-md-start">
      <v-col cols="4" md="3" class="pa-2" >
        <img :src="wordcloud"  class="w-100" />
      </v-col>
      <v-col  class="align-self-stretch d-none d-md-flex justyfy-center align-center" offset-md="6" md="3">
       <span class="text-md-h4 text-h5 font-weight-bold text-primary">Мамой быть <br> <span class=" text-secondary">не</span>легко!</span> 
      </v-col>
   
   
    </v-row>
  </v-parallax>
</template>

