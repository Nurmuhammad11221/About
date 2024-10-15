<template>

      <div class="footer__container">
            <div class="footer__title">
                <p>Связаться со мной</p>

            </div>

            <div class="footer__logo">
                <a href="https://www.facebook.com/?locale=ru_RU"><img  class="footer__logo__img"  :src="require('@/assets/facebook.png')" alt=""></a>
                <a href="https://www.instagram.com/707.nf/"><img  class="footer__logo__img"  :src="require('@/assets/instagram.png')" alt=""></a>
                <a href="https://t.me/Anf_707"><img  class="footer__logo__img"  :src="require('@/assets/telegram.png')" alt=""></a>
                <a href="https://mail.google.com/mail/u/0/#inbox"><img  class="footer__logo__img"  :src="require('@/assets/email.png')" alt=""></a>
                <a href="https://web.whatsapp.com/"><img  class="footer__logo__img"  :src="require('@/assets/whatsapp.png')" alt=""></a>
            </div>
      </div>

  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style>
      .footer__container{
          width: 100%;
          height: 250px;
          background-color: black;
      }
      
      .footer__title{
        color: white;
        text-align: center;
        font-weight: 400;
        font-size: 40px;
        padding: 30px;
      }

      .footer__logo{
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
        gap: 70px;
      }
  </style>