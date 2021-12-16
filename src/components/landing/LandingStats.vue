<template>
  <div class="main-stats mt-5 mb-5">
    <div class="stats-wrapper">
      <div class="stats-title d-flex justify-center text-h4 mt-10 mb-5">
        <b>Интернет магазин лицензионного программного обеспечения</b>
      </div>
      <div class="stats-container d-flex justify-space-between">
        <div class="stats-item" v-for="i in 3">
          <div class="stats-item-img"></div>
          <div class="stats-item-title text-h5 d-flex justify-center"><b>Преимущество</b></div>
          <div class="stats-item-text text-center mt-2">Наши цены позволяют вам сэкономить значительную часть ваших средств. В
            магазине скидки до 90%!
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingStats"
}
</script>

<style scoped>
.stats-item-text{
  color: gray;
}
</style>
