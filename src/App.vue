<template>
  <Header/>
  <MainScreen/>
  <HotManga/>
  <UpdateManga/>
</template>

<script>
import Header from '@/components/app/Header.vue'
import MainScreen from '@/components/MainScreen'
import HotManga from "@/components/HotManga";
import UpdateManga from "@/components/UpdateManga";

export default {
  name: 'App',
  components: {
    Header,
    MainScreen,
    HotManga,
    UpdateManga
  }
}
</script>

<style>

</style>
