<script setup>
import mainBanner from '../assets/images/main-banner.png'
import wordcloud from '../assets/images/wordcloud-infomama.webp'
</script>

<template>
  <v-parallax :src="mainBanner" height="75vh">
    <v-row no-gutters>
      <v-col cols="8">

      </v-col>
      <v-col cols="4">
        <img :src="wordcloud" style="object-fit: contain; max-height: 70vh" />
      </v-col>
      <!-- <v-col cols="4">
        <v-card class="mx-8 pa-3">
          <h3 class="mb-2">
            Роддом, больницы, узи, анализы, специалисты
          </h3>
          <h3 class="mb-2">
            Подготовка к родам, гимнастика, фитнес, купоны на скидку
          </h3>
          <h3>
            Няня и уход за ребёнком
          </h3>
        </v-card>
      </v-col>
      <v-col cols="4">
        <v-card class="mx-8 pa-3">
          <h3 class="mb-2">
            Школа, кружки и секции
          </h3>
          <h3 class="mb-2">
            Садик, школы, колледжи, ВУЗы, репетиторы
          </h3>
          <h3>
            Юридическая помощь
          </h3>
        </v-card>
      </v-col>
      <v-col cols="4">
        <v-card class="mx-8 pa-3">
          <h3 class="mb-2">
            Развлечения и отдых
          </h3>
          <h3 class="mb-2">
            Хобби для мам
          </h3>
          <h3>
            Барахолка и доставка продуктов
          </h3>
        </v-card>
      </v-col> -->
    </v-row>
  </v-parallax>
</template>

