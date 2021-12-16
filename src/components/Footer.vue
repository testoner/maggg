<template>
  <div class="footer d-flex justify-center pt-2 pb-2">
    <div class="footer-wrapper d-flex ml-5 mr-5 align-center">
      <div class="footer-block d-flex align-center">
        <div class="footer-logo">
          <p class="text-h4 mb-1"><b>Soft store</b></p>
          <p class="text-subtitle-1">@2021 SoftShop.Все права защищены</p>
        </div>
        <div class="footer-about text-body-1">
          <div class="mb-2"><b>О магазине:</b></div>
          <div class='mb-2'>О нас</div>
          <div class='mb-2'>Гарантии</div>
          <div class='mb-2'>Контакты</div>
          <div>Отзывы</div>
        </div>
      </div>
      <div class="footer-contact mt-5">
        <div class="mb-2">Быстрая связь с нами:</div>
        <div class="contact-item">Написать в Telegram</div>
        <div class="contact-item">Написать на почту</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
  .footer{
    border-top: 1px solid rgba(157, 157, 157, 0.42);
  }
  .footer-wrapper{
    max-width: 1200px;
    flex-basis: 100%;
    justify-content: space-between;
  }

  .footer-block{
    max-width: 500px;
    flex-basis: 100%;
    justify-content: space-between;
  }

  .contact-item{
    margin-bottom: 10px;
    padding: 20px;
    border-radius: 15px;
    background-color: black;
    color: white;
    cursor: pointer;
  }
</style>
