<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import ForUsers from "@/components/ForUsers.vue";
import ForPartners from "@/components/ForPartners.vue";
import RoadMap from "@/components/roadMap.vue";
import VideoLogo from '@/components/VideoLine.vue';
import Contacts from '@/components/Contacts.vue';
</script>

<template>
  <HelloWorld />
  <ForUsers id="for-users"/>
  <VideoLogo />
  <ForPartners id="partners" />
  <RoadMap  id="roadmap"/>
  <Contacts id="contacts"/>
</template>


