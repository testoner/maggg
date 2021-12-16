<template>
  <div class="main-sales mt-5 mb-5">
    <div class="sales-wrapper">
      <div class="sales-container">
        <v-tabs v-model="tab" class="d-flex justify-center">
          <v-tab class="text-body-1"><b>Microsoft Windows</b></v-tab>
          <v-tab class="text-body-1"><b>Microsoft Office</b></v-tab>
          <v-tab class="text-body-1"><b>Starter Packs</b></v-tab>
          <v-tab class="text-body-1"><b>Мультимедиа</b></v-tab>
        </v-tabs>
        <v-tabs-items v-model="tab" >
          <v-tab-item v-for="j in 4" :key="j">
            <div class="sales-items mt-8 d-flex justify-space-around flex-wrap">
              <div class="sales-item d-flex align-center" v-for="i in 4" :key="i">
                <div class="sale-item-img">
                  <img src="../../assets/img1.png" alt="#" width="350px">
                </div>
                <div>
                  <div class="text-subtitle-1 sale-hit">хит продаж</div>
                  <div class="text-6 sale-item-title text-h5 mb-3"><b>windows 10</b></div>
                  <div class="sales-item-about text-body-2">Тип</div>
                  <div class="sales-item-about text-body-2">Язык</div>
                  <div class="sales-item-about text-body-2">Разрядность</div>
                  <div class="sales-item-about text-body-2">Стоимость</div>
                  <div class="sales-item-btn">Кнопка купить</div>
                </div>
              </div>
            </div>
          </v-tab-item>
        </v-tabs-items>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingSales",
  data() {
    return {
      tab: null,
    }
  },
}
</script>

<style scoped>
.main-sales {
  display: flex;
  justify-content: center;
}

.sales-wrapper {
  max-width: 1200px;
  flex-basis: 100%;
}

.sales-container {

  max-width: 1200px;
  flex-basis: 100%;
}

.sales-item{
  margin-bottom: 20px;
  padding: 20px 70px 20px 0!important;
  border: 1px solid gray;
  border-radius: 15px;
}

.sales-item-about{
  color: gray;
}

.sale-hit{
  width: 110px;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 15px;
  background-color: #5f5fda;
  color: white;
}

.sales-item-btn{
  margin-top:20px;
  padding: 15px 20px 15px 20px;
  border-radius: 15px;
  border: 1px solid gray;
  cursor: pointer;
}
</style>
