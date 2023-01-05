<script setup></script>

<template>
    <v-timeline side="end" class="bg-tertiary" style="height: 500px">
      <v-timeline-item dot-color="primary" size="small">
        <div class="text-h6">1-ый квартал 2023</div>
        <div class="d-flex">
          <div>
            <div class="text-h10">Создание промо-сайта</div>
            <div class="text-h10">Концепт приложения</div>
            <div class="text-h10">Начало разработки сайта приложения</div>
          </div>
        </div>
      </v-timeline-item>

      <v-timeline-item dot-color="secondary" size="small">
        <template v-slot:opposite>
          <div class="text-h6">2-ой квартал 2023</div>
          <div class="d-flex">
            <div>
              <div class="text-h10">Начало разработки мобильного приложения</div>
              <div class="text-h10">Оптимизация сайта</div>
            </div>
          </div>
        </template>
      </v-timeline-item>

      <v-timeline-item dot-color="primary" size="small">
        <div class="text-h6">3-ий квартал 2023</div>
        <div class="d-flex">
          <div>
            <div class="text-h10">Тестирование и исправление ошибок приложения</div>
            <div class="text-h10">Публикация сайта</div>
            <div class="text-h10">Техническая поддержка приложения</div>
          </div>
        </div>
      </v-timeline-item>

      <v-timeline-item dot-color="secondary" size="small">
        <template v-slot:opposite>
          <div class="text-h6">4-ый квартал 2023</div>
          <div class="d-flex">
            <div>
              <div class="text-h10">Релиз продукта</div>
              <div class="text-h10">Размещения приложения в AppStore и PlayMarket</div>
            </div>
          </div>
        </template>
      </v-timeline-item>
    </v-timeline>
</template>
