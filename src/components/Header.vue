<template>
  <div :style="{ backgroundImage: 'url(' + require('@/assets/1.1.png') + ')' }"  class="header__img">

    <div class="container">
      <div class="Header__title">

        <h1 style="margin: 0; color: black;">Добро пожаловать на мой сайт</h1>
        
      </div>
      
      
    </div>
  </div>
</template>


<script>
export default {

}
</script>

<style>
  .Header__title{
    display: flex;
    justify-content: center;
    align-items: center; 
    height: 100vh;
  }
  .header__img{

    height: 100vh;
    width: 100%;
    box-sizing: border-box;
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>