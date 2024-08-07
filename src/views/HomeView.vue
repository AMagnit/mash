<template>

  <div class="row">

    <div class="col-12">

      <h1 class="mt-5 display-1">

        <span class="d-inline-block">

          Добро

        </span>


        <br>

        <span class="d-inline-block animate__animated animate__fadeIn animate__delay-1s">
          пожаловать
        </span>
        <br>

        <span class="d-inline-block animate__animated animate__fadeInLeft animate__delay-2s">
          в <img src="/img/logo.svg" width="234" class="w-32 sm:w-40 md:w-56 lg:w-72 xl:w-80">
        </span>
      </h1>

    </div>


  </div>


  <div class="mt-3 container text-center h3 animate__animated animate__fadeIn animate__delay-3s">

      Пожалуйста, заполните форму для регистрации на платформе в качестве партнера
  </div>



  <div class="row animate__animated animate__fadeIn animate__delay-4s mt-3">

    <div class="col-12 mb-4">
      <small>Ваше имя</small>
      <input type="text"

             class="form-control form-control-lg text-capitalize" placeholder="Gordon">
    </div>

    <div class="col-12 mb-4">
      Электронная почта
      <input type="email" class="form-control form-control-lg" placeholder="name@example.com">
    </div>


    <div class="col-12 mb-4">
      Телефон
      <input type="number" class="form-control form-control-lg" placeholder="+1 234 456 789">
    </div>

    <div class="col-12 mb-4">
      Ссылка на основной аккаунт в социальных сетях
      <input type="text" class="form-control form-control-lg" placeholder="@">
    </div>



    <div class="col-12 mb-4">

      <how-many-bloggers/>

    </div>

    <div class="col-12 mb-4">

      <all-audience/>
    </div>

    <div class="col-12 mb-4 text-center">


      <span class="btn btn-warning btn-lg rounded-pill mb-3">Присоединится</span><br>

      Нажимая кнопку, вы даете согласие на обработку персональных данных и соглашаетесь с политикой конфиденциальности
    </div>

    <div class="col-12 col-md-4 mb-4 text-center">

      <img src="/img/logo.svg" width="234" class="w-32 sm:w-40 md:w-56 lg:w-72 xl:w-80">

    </div>


    <div class="col-12 col-md-4 mb-4 text-light h3 pt-4  text-center">

      Info@fanzoone.com

    </div>

    <div class="col-12 col-md-4 mb-4 text-light h3 pt-4  text-center">

      +37060410209

    </div>

  </div>







</template>

<script setup>
import HowManyBloggers from '@/components/main_page/HowManyBloggers.vue'
import AllAudience from '@/components/main_page/AllAudience.vue'
</script>

<style>
input{
  background-color: #7c5dff !important;


  border-bottom: 2px solid red;

  color: #FFFFFF !important;
}

input, select, textarea{
  color: #FFFFFF;
}


</style>



