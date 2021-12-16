<template>
  <div class="main-category">
    <div class="category-title text-h4 mt-15 mb-5"><b>Категории</b></div>
    <div class="category-container d-flex">
      <div class="category-item" v-for="i in 6" :key="i">
        <p class="text-body-1">item {{ i }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingCategory"
}
</script>

<style scoped>
.category-container {
  flex-wrap: wrap;
  justify-content: space-around;
}

.category-item {
  width: 390px;
  height: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-image: url('../../assets/small3.png');
  border-radius: 15px;
  color: white;
  cursor: pointer;
}

.category-title {
  display: flex;
  justify-content: center;
}

</style>
