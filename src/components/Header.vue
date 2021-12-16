<template>
  <div>
    <div class="header pt-5 pb-5">
      <div class="header-wrapper d-flex ml-5 mr-5">
        <div class="header-block d-flex">
        <div class="header-logo mr-5 text-h4">
          <b>SoftShop</b>
        </div>
        <div class="header-bar d-flex text-body-1">
          <div>Каталог</div>
          <div>О нас</div>
          <div>Контакты</div>
        </div>
        </div>
        <div class="header-history text-body-1">
          <b>История покупок</b>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Header',

    data(){
      return {

    }
    },
  }
</script>
<style scoped>
  .header{
    display: flex;
    justify-content: center;
    border-bottom: 1px solid rgba(157, 157, 157, 0.42);
  }
  .header-wrapper{
    max-width: 1200px;
    flex-basis: 100%;
    justify-content: space-between;
    align-items: center;
  }
  .header-block{
    max-width: 500px;
    flex-basis: 100%;
    justify-content: space-between;
    align-items: center;
  }
  .header-bar{
    max-width: 250px;
    flex-basis: 100%;
    justify-content: space-between;
  }
</style>
