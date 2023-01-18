<script setup>
import { onMounted} from "vue";
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger.js";
gsap.registerPlugin(ScrollTrigger);

onMounted(() => {
  let team = document.querySelectorAll(".team");

  team.forEach((element) => {
    gsap.from(element, {
      scrollTrigger: {
        trigger: element,
        start: "top bottom-=200px",
        once: true,
        // toggleActions: "restart pause resume pause",
      },
      x: -100,
      duration: 2,
      opacity: 0,
      ease: "bounce.out",
    });
  });
});
</script>
<template>
  <div class="bg-team">
    <v-container>
      <v-row>
        <v-col>
          <v-card-title class="text-md-span text-h5 font-weight-bold">
            Команда проекта
          </v-card-title>
        </v-col>
      </v-row>
      <v-row>
        <v-col
          class="d-flex justify-center align-center flex-wrap team_wrapper"
          ref="main"
        >
          <div class="text-center mentor-card team">
            <v-avatar size="150" tile class="rounded-circle">
              <v-img src="../assets/images/ivan.jpeg"></v-img>
            </v-avatar>

            Чукавин Иван
          </div>
          <div class="text-center mentor-card team">
            <v-avatar size="150" tile class="rounded-circle">
              <v-img src="../assets/images/alena.jpg"></v-img>
            </v-avatar>

            Шкляева Елена
          </div>
          <div class="text-center mentor-card team">
            <v-avatar size="150" tile class="rounded-circle">
              <v-img src="../assets/иконки/qbit.png"></v-img>
            </v-avatar>
            <div>Клуб Кубит</div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
  

  <style lang="scss" scoped>
  .v-img{
    filter: grayscale(100%);
  }
.bg-team {
  background: rgba(134, 133, 171, 0.1);
}
.team_wrapper {
  column-gap: 50px;
}
.mentor-card {
  max-width: 200px;
}
.hyphenation {
  word-break: keep-all;
}
</style>