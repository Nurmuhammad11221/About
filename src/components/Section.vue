<template>
    <div class="section__container">

        <h1 class="section__text">Обо мне</h1>

        <div style="display: flex;">

            <div>
                <img class="section__img" :src="require('@/assets/1.2.png')" alt="Rasm">
            </div>
            <div>
                <h2 style="margin-left: 120px;margin-top: 20px; color: white;">Зубенко Михаил Петрович</h2>
                <p class="section__title">Я могу делать семейные портреты в студии, работать <br> на показах мод, снимать моделей для рекламы или <br> фотографировать на свадьбах. Отдельное <br> направление -- съёмки предметов и еды, которые <br> заказывают для рекламы или меню ресторанов. Я <br> могу быть криминальным фотографом мест <br> преступлений, охотником за знаменитостями или <br> снимать диких животных для журналов о природе. Я <br> востребованный специалист в новостных изданиях, <br> работаю в паре с журналистом и могу оказаться где <br> угодно: от гламурной вечеринки до места пожара, <br> наводнения и даже вооруженного конфликта. Моя <br> профессия будет востребована и в будущем, ведь 80% <br> успеха фотографии -- это не качество техники, а <br> профессионализм фотографа. </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .section__container{
        background-color: #0E1C25;
        height: 650px;
        
    }
    .section__text{
        text-align: center;
    }
    .section__img{
        width: 500px;
        height: 550px;
        margin-top: 20px;  
        margin-left: 180px; 
    }
    .section__title{
        font-weight: 300;
        font-size: 16px;
        line-height: 20px;
        color: white;
        margin-top: 30px;
        margin-left: 120px;
    }
</style>