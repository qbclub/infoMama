<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import ForUsers from "@/components/ForUsers.vue";
import ForPartners from "@/components/ForPartners.vue";
import Team from "@/components/Team.vue";
import RoadMap from "@/components/roadMap.vue";
import VideoLogo from "@/components/VideoLine.vue";
import Contacts from "@/components/Contacts.vue";
import TextCarousel from "@/components/TextCarousel.vue";

</script>

<template>
  <HelloWorld />
  <TextCarousel />
  <ForUsers id="for-users" />
  <VideoLogo />
  <ForPartners id="partners" />
  <Team id="team"/>
  <RoadMap id="roadmap" />
  <Contacts id="contacts" />
</template>


