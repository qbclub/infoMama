<script setup>
//
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
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
                <v-card-title> Заголовок</v-card-title>
                <v-card-text> тут текст</v-card-text>
              </v-card>
            </v-hover>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <div class="d-none d-md-flex"><img
      src="../assets/иконки/purple.png"
      style="top: 10px; left: 10px"
      id="dot_1"
    />
    <img
      src="../assets/иконки/yellow.png"
      style="top: 10px; right: 10px"
      id="dot_2"
    />
    <img
      src="../assets/иконки/purple.png"
      style="bottom: 10px; right: 10px"
      id="dot_3"
    />
    <img
      src="../assets/иконки/yellow.png"
      style="bottom: 10px; left: 10px"
      id="dot_4"
    /></div>
    
  </div>
</template>
<style lang="scss" scoped>
.bg {
  background: #b9f8bf;
  position: relative;
}
img {
  height: 20px;
  position: absolute;
}
</style>
