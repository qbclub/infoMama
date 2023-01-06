<script setup>
import { ref } from "vue";
import { useRouter } from "vue-router";

let props = defineProps({
  roadMapRoute: String,
  partnersRoute: String,
  usersRoute: String,
});

let drawer = ref(false);
let router = useRouter();
</script>

<template>
  <!-- <v-app-bar border class="d-flex">
      <div>Пользователям</div>
      <div>Партнёрам</div>
      <div>Дорожная карта</div>
  </v-app-bar> -->
  <v-app-bar prominent>
    <v-app-bar-nav-icon
      variant="text"
      @click.stop="drawer = !drawer"
    ></v-app-bar-nav-icon>
    <video width="100" autoplay loop muted playsinline>
      <source src="../../assets/vk.mp4" />
    </video>

    <v-toolbar-title> ИнфоМама </v-toolbar-title>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" temporary>
    <v-list-item
      prepend-icon="mdi-view-dashboard"
      title="Пользователям"
      value="home"
      @click="router.push(usersRoute ? usersRoute : '/forUsers')"
    ></v-list-item>
    <v-list-item
      prepend-icon="mdi-forum"
      title="Партнёрам"
      value="home"
      @click="router.push(partnersRoute ? partnersRoute : '/forPartners')"
    ></v-list-item>
    <v-list-item
      prepend-icon="mdi-view-dashboard"
      title="Дорожная карта"
      value="home"
      @click="router.push(roadMapRoute ? roadMapRoute : '/roadMap')"
    ></v-list-item>
  </v-navigation-drawer>
</template>
