<script setup>
import greenDot from "../assets/иконки/green.png";
import purpleDot from "../assets/иконки/purple.png";
import yellowDot from "../assets/иконки/yellow.png";
const sliderText = [
  [greenDot, "удобное приложение"],
  [purpleDot, "актуальная информация"],
  [yellowDot, "полезные справочники"],
  [greenDot, "заполняется пользователями"],
  [purpleDot, "интересно для бизнеса"],
];
</script>
<template>
  <v-container>
    <v-row class="justify-center">
      <v-col>
        <div class="d-flex slider">
          <div v-for="(item, i) in sliderText" :key="i" class="ma-2">
            <img :src="item[0]" />
            {{ item[1] }}
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>
<style lang="scss" scoped>
.slider {
  // scroll-behavior: smooth;
  overflow-x: auto;
  cursor: all-scroll;
  line-height: 40px;
  div {
    white-space: nowrap;
    display: flex;
    align-items: center;
    color: rgba(0, 0, 0, 0.5);
    img {
      height: 20px;
      padding-right: 5px;
    }
  }
}
// * {
//   scrollbar-width: 0px;
// }

// *::-webkit-scrollbar {
//   width: 0;
// }
</style>