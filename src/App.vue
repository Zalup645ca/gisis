<template>
    <v-app>
    <v-main>
 <HelloWorld />
  <!----<MainProduct/>-->
  <!-----<AdminPanel/>-->
  </v-main>
  </v-app>
 

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
//import AdminPanel from './components/AdminPanel.vue'
//import MainProduct from './components/MainProduct.vue'
export default {
  name: 'App',
  components: {
    HelloWorld
  //  MainProduct,
    //AdminPanel
  }
}
</script>

<style>

</style>
