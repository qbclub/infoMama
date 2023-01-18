<script setup>
</script>

<template>
  <div>
    <v-container>
      <v-row>
        <v-col>
          <v-card-title class="text-md-span text-h5 font-weight-bold">
            Партнерам и инвесторам
          </v-card-title>
        </v-col>
      </v-row>

      <v-row class="card-container">
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100 bg-secondary rounded-xl">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Вдохновлено</v-card-title>
                <v-card-text>
                  Самым большим женским ВК сообществом Глазова -
                  <a href="https://vk.com/mama_glazova">
                    <b>Мамы Глазова.</b>
                  </a>
                </v-card-text>
              </v-card>
            </v-hover>
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Придумано</v-card-title>
                <v-card-text>В рамках разработки цифровых решений платформы «Умный город Росатома».</v-card-text>
              </v-card>
            </v-hover>
          </div>
        </v-col>
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100 bg-primary rounded-xl">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Поддержано</v-card-title>
                <v-card-text> Союзом активных граждан и предпринимателей в сфере развития цифровизации «Смарт-Глазов».</v-card-text>
              </v-card>
            </v-hover>
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title>
                  Привлекательно</v-card-title
                >
                <v-card-text> Для предпринимателей, продавцов товаров, работ и услуг.</v-card-text>
              </v-card>
            </v-hover>
          </div>
        </v-col>
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100 bg-accent rounded-xl">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Интересно</v-card-title>
                <v-card-text> Высоким доверием аудитории. Мамы помогают информацией мамам.</v-card-text>
              </v-card>
            </v-hover>
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Выгодно</v-card-title>
                <v-card-text> Для рекламодателей - понятная целевая аудитория. </v-card-text>
              </v-card>
            </v-hover>
          
          </div>
        </v-col>
      </v-row>
      <!-- <v-row>
        <v-col class="d-flex flex-column" cols="12" md="4" offset="md-4">
          <div class="w-95 h-100 bg-primary rounded-xl">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title class="text-center"> Ищем</v-card-title>
                <v-card-text> Партнеров, инвесторов</v-card-text>
              </v-card>
            </v-hover>
        
          
          </div>
        </v-col>
      </v-row> -->
    </v-container>
  </div>
</template>
<style lang="scss" scoped>
</style>



