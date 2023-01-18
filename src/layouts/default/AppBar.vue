<script setup>
import { ref } from "vue";
import { useRouter } from "vue-router";

let props = defineProps({
  roadMapRoute: String,
  partnersRoute: String,
  usersRoute: String,
});

const options = {
  duration: 300,
  offset: 0,
  easing: "easeInOutCubic",
};

let drawer = ref(false);
let router = useRouter();
</script>

<template>
  <v-app-bar prominent>
    <v-app-bar-nav-icon
      variant="text"
      @click.stop="drawer = !drawer"
    ></v-app-bar-nav-icon>
    <video width="100" playsinline autoplay loop muted>
      <source src="../../assets/vk.mp4" />
    </video>

    <v-toolbar-title class="font-weight-bold"> ИнфоМама </v-toolbar-title>
  </v-app-bar>

  <v-navigation-drawer v-model="drawer" temporary>
    <a href="#for-users">
      <v-list-item
        prepend-icon="mdi-account-supervisor"
        title="Мамам и папам"
      ></v-list-item>
    </a>
    <a href="#partners">
      <v-list-item prepend-icon="mdi-hands-pray" title="Партнёрам"></v-list-item>
    </a>
    <a href="#team">
      <v-list-item prepend-icon="mdi-account-group-outline" title="Команда"></v-list-item>
    </a>
    <a href="#roadmap">
      <v-list-item
        prepend-icon="mdi-map-outline"
        title="Дорожная карта"
      ></v-list-item>
    </a>
    <a href="#contacts">
      <v-list-item
        prepend-icon="mdi-card-account-phone-outline"
        title="Контакты"
      ></v-list-item>
    </a>
  </v-navigation-drawer>
</template>
<style lang="scss" scoped>
a {
  text-decoration: none;
  color: black;
}
.v-toolbar__content > .v-toolbar-title {
   margin-inline-start: 0; 
}
</style>

