<template>
  <v-app>
    <v-main>
      <TopBar />
      <Content />
    </v-main>
  </v-app>
</template>

<style>

</style>

<script>
import TopBar from './components/TopBar/TopBar.vue'
import Content from './components/Content/Content.vue'
export default{
  components:{
    TopBar,
    Content
  }
}
</script>
