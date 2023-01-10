<script setup>
</script>

<template>
  <div class="bg">
    <v-container>
      <v-row>
        <v-col>
          <v-card-title class="text-md-span text-h5 font-weight-bold">
            Мамам и папам
          </v-card-title>
        </v-col>
      </v-row>

      <v-row class="card-container">
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Образование</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Школы',
                      'Детские сады',
                      'Вузы',
                      'Колледжи',
                      'Репетиторы',
                      'Кружки',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
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
                <v-card-title> Медицина</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Врачи',
                      'Больницы',
                      'Поликлиники',
                      'Аптеки',
                      'Массаж',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
              </v-card>
            </v-hover>
          </div>
        </v-col>
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Досуг</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Праздники',
                      'Выставки',
                      'Кино',
                      'Путешествия',
                      'Театры',
                      'Рестораны',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
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
                <v-card-title> Красота</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Салоны',
                      'Парикмахерские',
                      'Спорт',
                      'Фитнес',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
              </v-card>
            </v-hover>
          </div>
        </v-col>
        <v-col class="d-flex flex-column" cols="12" md="4">
          <div class="w-95 h-100">
            <v-hover v-slot="{ isHovering, props }" open-delay="200">
              <v-card
                width="auto"
                class="rounded-xl ma-2"
                :elevation="isHovering ? 16 : 2"
                :class="{ 'on-hover': isHovering }"
                v-bind="props"
              >
                <v-card-title> Работа</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Вакансии',
                      'Поиск',
                      'Обучение',
                      'Услуги',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
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
                <v-card-title> Барахолка</v-card-title>
                <v-card-text>
                  <v-chip
                    v-for="(item, index) in [
                      'Куплю',
                      'Продам',
                      'Отдам',
                      'Аренда',
                      'Разумное потребление',
                    ]"
                    class="ma-1"
                    :key="index"
                  >
                    {{ item }}
                  </v-chip> </v-card-text
                ><img
                  src="../assets/иконки/purple.png"
                  class="card-icon ma-2"
                />
              </v-card>
            </v-hover>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <!-- <div class="d-none d-md-flex">
      <img
        src="../assets/иконки/purple.png"
        style="top: 10px; left: 10px"
        id="dot_1"
        class="dot"
      />
      <img
        src="../assets/иконки/yellow.png"
        style="top: 10px; right: 10px"
        id="dot_2"
        class="dot"
      />
      <img
        src="../assets/иконки/purple.png"
        style="bottom: 10px; right: 10px"
        id="dot_3"
        class="dot"
      />
      <img
        src="../assets/иконки/yellow.png"
        style="bottom: 10px; left: 10px"
        id="dot_4"
        class="dot"
      />
    </div> -->
  </div>
</template>
<style lang="scss" scoped>
.bg {
  background: #b9f8bf;
  position: relative;
}
.card-icon {
  height: 30px;
  position: absolute;
  top: 5px;
  right: 5px;
}
.v-chip:hover,
.v-chip:active {
  background: #fee792;
}
</style>
