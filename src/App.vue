<template>
  <v-app>
    <Header></Header>
    <Landing></Landing>
    <Footer></Footer>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
    Header: ()=> import('./components/Header.vue'),
    Footer: ()=> import('./components/Footer.vue'),
    Landing: ()=> import('./components/LandingPage.vue')
  },
  data: () => ({
    //
  }),
};
</script>
