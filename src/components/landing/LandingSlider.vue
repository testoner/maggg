<template>
  <div class="first-slider d-flex justify-center ">
    <v-carousel class="slider" hide-delimiters cycle
                show-arrows-on-hover>
      <v-carousel-item
          v-for="(item,i) in items"
          :key="i"
          :src="item.src"
      ></v-carousel-item>
    </v-carousel>
  </div>
</template>

<script>
export default {
  name: "LandingSlider",
  data() {
    return {
      items: [
        {
          src: './banner1.png',
        },
        {
          src: './about-slide4.png',
        },
        {
          src: './small3.png',
        },
        {
          src: './img1.png',
        },
      ],
    }
  },
}
</script>

<style scoped>

.first-slider{
  max-width: 1200px;
  flex-basis: 100%;
  display: flex;
  justify-content: center;
}

.slider{
  max-width: 1000px!important;
  flex-basis: 100%;
}
</style>
