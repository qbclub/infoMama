<script setup>
import { ref } from "vue";

let drawer = ref(false);

</script>

<template>
  <!-- <v-app-bar border class="d-flex">
      <div>Пользователям</div>
      <div>Партнёрам</div>
      <div>Дорожная карта</div>
  </v-app-bar> -->
      <v-app-bar color="primary" prominent>
        <v-app-bar-nav-icon
          variant="text"
          @click.stop="drawer = !drawer"
        ></v-app-bar-nav-icon>

        <v-toolbar-title> Основная информация </v-toolbar-title>

        <v-spacer></v-spacer>
      </v-app-bar>

      <v-navigation-drawer v-model="drawer" temporary>
        <v-list-item prepend-icon="mdi-view-dashboard" title="Пользователям" value="home"></v-list-item>
        <v-list-item prepend-icon="mdi-forum" title="Партнёрам" value="home"></v-list-item>
        <v-list-item prepend-icon="mdi-view-dashboard" title="Дорожная карта" value="home"></v-list-item>
      </v-navigation-drawer>

</template>
