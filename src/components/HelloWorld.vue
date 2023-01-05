<script setup>
import mainBanner from '../assets/images/main-banner.png'
</script>

<template>
  <v-parallax :src="mainBanner" height="60vh" class="d-flex text-center align-center">
    <v-row no-gutters>
      <v-col cols="4">
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
      </v-col>
    </v-row>
  </v-parallax>
</template>

