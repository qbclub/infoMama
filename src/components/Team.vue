<script setup>
// import { gsap } from "gsap";

//   mounted() {
//     gsap.from(".team", {
//       scrollTrigger: {
//         trigger: ".team",
//         start: "top bottom-=200px",
//         once: true,
//         toggleActions: "restart pause resume pause",
//       },
//       y: 30,
//       duration: 2,
//     });
//   },
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
        <v-col class="d-flex justify-center align-center flex-wrap team">
          <div class="text-center mentor-card">
            <v-avatar size="150" tile class="rounded-circle">
              <v-img src="../assets/images/ivan.jpeg"></v-img>
            </v-avatar>

            Чукавин Иван
          </div>
          <div class="text-center mentor-card">
            <v-avatar size="150" tile class="rounded-circle">
              <v-img src="../assets/images/alena.jpg"></v-img>
            </v-avatar>

            Шкляева Елена
          </div>
          <div class="text-center mentor-card">
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
.bg-team {
  background: rgba(134, 133, 171, 0.1);
}
.team {
  column-gap: 50px;
}
.mentor-card {
  max-width: 200px;
}
.hyphenation {
  word-break: keep-all;
}
</style>