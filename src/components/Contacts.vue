<script setup></script>

<template>
  <div class="contacts">
    <v-container>
      <v-row class="justify-center">
        <v-col cols="6" md="2" class="text-center">
          <p class="font-weight-bold">Контакты <br /></p>
          <div>
            <p>тел. <a href="tel:89127559182"> 89127559182</a></p>
            <p  prepend-icon="mdi-view-dashboard">
              <a href="https://vk.com/id38022537" target="_blank"><img src="../assets/иконки/vk.png" style="width:30px" alt=""> </a>
            </p>
          </div>
        </v-col>
        <v-col class="font-weight-bold d-flex align-center" cols="6" md="2" >
          <a href="https://qbit-club.com/" target="_blank">
            Сделано в Кубит
          </a></v-col
        >
      </v-row>
    </v-container>
  </div>
</template>
<style lang="scss" scoped>
.contacts {
  background: rgba(254, 231, 146, 0.2);
}
</style>
