<template>
  <v-app>
    <Header/>
    <nuxt/>
      <v-footer fixed>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
// import Header from '@/components/Header.vue' 
export default {
  // components: {
  //   Header
  // }
  
}
</script>
