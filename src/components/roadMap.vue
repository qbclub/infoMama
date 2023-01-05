<script setup></script>

<template>
  <div class="bg-tertiary">
    <v-container>
      <v-row>
        <v-col>
          <span class="text-md-h4 text-h5 font-weight-bold pl-0 mb-6">
           Дорожная карта
          </span>
        </v-col>
      </v-row></v-container
    >

    <v-timeline side="end">
      <v-timeline-item dot-color="primary" size="small">
        <div class="text-h6">1-ый квартал 2023</div>
        <div class="d-flex">
          <div>
            <div class="text-h10">Создание промо-сайта</div>
            <div class="text-h10">Концепт</div>
            <div class="text-h10">Начало разработки приложения</div>
          </div>
        </div>
      </v-timeline-item>

      <v-timeline-item dot-color="secondary" size="small">
        <template v-slot:opposite>
          <div class="text-h6">2-ой квартал 2023</div>
          <div class="d-flex">
            <div>
              <div class="text-h10">
                Развитие функциональности
              </div>
              <div class="text-h10">Оптимизация</div>
            </div>
          </div>
        </template>
      </v-timeline-item>

      <v-timeline-item dot-color="primary" size="small">
        <div class="text-h6">3-ий квартал 2023</div>
        <div class="d-flex">
          <div>
            <div class="text-h10">
              Тестирование и исправление
            </div>
            <div class="text-h10">Публикация сайта</div>
            <div class="text-h10">Техническая поддержка</div>
          </div>
        </div>
      </v-timeline-item>

      <v-timeline-item dot-color="secondary" size="small">
        <template v-slot:opposite>
          <div class="text-h6">4-ый квартал 2023</div>
          <div class="d-flex">
            <div>
              <div class="text-h10">Релиз продукта</div>
              <div class="text-h10">
                Размещения в AppStore, <br> PlayMarket
              </div>
            </div>
          </div>
        </template>
      </v-timeline-item>
    </v-timeline>
  </div>
</template>
