<template>
  <div class="main-news">
    <div class="news-wrapper mr-5 ml-5">
      <div class="news-title text-h4 mb-5">
        <b>Новости & Статьи</b>
      </div>
      <div class="news-container d-flex justify-space-between">
        <div class="news-item" v-for="i in 3" :key="i">
          <div class="news-item-img ">
            <img src="../../assets/Windows.png" alt="#">
          </div>
          <div class="news-item-title text-h6 d-flex justify-center">
            <b>Заголовок статьи новостей</b>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingNews"
}
</script>

<style scoped>
.news-title {
  display: flex;
  justify-content: center
}

.news-item-img{
  border-radius: 15px;
  width: 350px;
}
.news-item-img img{
  width: 100%;
  border-radius: 15px;
}
</style>
