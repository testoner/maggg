<template>
  <div class="main mt-5 mb-5">
    <div class="main-wrapper ml-5 mr-5">
      <LandingSlider>
      </LandingSlider>
      <LandingCategory>
      </LandingCategory>
      <LandingSales>
      </LandingSales>
      <LandingStats>
      </LandingStats>
      <LandingNews>
      </LandingNews>
      <LandingAbout>
      </LandingAbout>
    </div>
  </div>
</template>

<script>

export default {
  name: "LandingPage",

  components:{
    LandingSlider: () => import('./landing/LandingSlider'),
    LandingCategory: () => import('./landing/LandingCategory'),
    LandingSales: () => import('./landing/LandingSales'),
    LandingNews: () => import('./landing/LandingNews'),
    LandingStats: () => import('./landing/LandingStats'),
    LandingAbout: () => import('./landing/LandingAbout'),
  },

}
</script>

<style scoped>
.main {
  display: flex;
  justify-content: center;
}

.main-wrapper {
  flex-basis: 100%;
  max-width: 1200px;
}

</style>
