<script setup>
import { breakpointsTailwind, useBreakpoints } from "@vueuse/core";

const breakpoints = useBreakpoints(breakpointsTailwind);

const md = breakpoints.smallerOrEqual("md");
// const largerThanSm = breakpoints.greater('sm') // only larger than sm
// const lgAndSmaller = breakpoints.smallerOrEqual('lg') // lg and smaller
// const smallerThanLg = breakpoints.smaller('lg') // only smaller than lg
</script>


<template>
  <div class="bg-tertiary">
    <v-container>
      <v-row>
        <v-col>
          <v-card-title class="text-md-span text-h5 font-weight-bold pl-0 mb-6">
            Дорожная карта
          </v-card-title>
        </v-col>
      </v-row>

      <v-row>
        <v-col>
          <v-timeline side="end" :direction="md ? 'vertical' : 'horizontal'">
            <v-timeline-item dot-color="primary" fill-dot size="small">
              <div class="font-weight-bold">1кв. 2023</div>

              <div>Промо-сайт</div>
              <div>Концепт</div>
              <div>Начало разработки</div>
            </v-timeline-item>

            <v-timeline-item dot-color="secondary" fill-dot size="small">
              <template v-slot:opposite>
                <div class="font-weight-bold">2кв. 2023</div>

                <div>Развитие</div>
                <div>Оптимизация</div>
              </template>
            </v-timeline-item>

            <v-timeline-item dot-color="primary" fill-dot size="small">
              <div class="font-weight-bold">3кв. 2023</div>
              <div>
                Тестирование, <br />
                исправление
              </div>
            </v-timeline-item>

            <v-timeline-item dot-color="secondary" fill-dot size="small">
              <template v-slot:opposite>
                <div class="font-weight-bold">4кв. 2023</div>
                <div>Релиз продукта</div>
              </template>
            </v-timeline-item>
          </v-timeline>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
