<template>

    <div class="nav__container">
        <div class="right__nav">
            <h1>Proweb</h1>
        </div>


      

        <div class="left__nav">
            <a class="nav__link" href="#">Обо мне</a>
            <a class="nav__link" href="#">Мои работы</a>
            <a class="nav__link" href="#">Контакты</a>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>

    .nav__container{
        height: 76px;
        background: black;
        color: white;
        display: flex;
        justify-content: space-evenly;
        align-items: center ;

    }

    h1{
        color: white;
        font-size: 40px;
        font-weight: 700;


    }
    .left__nav{
        display: flex;
        justify-content: space-between;
        width: 350px;
        height: 100%;
        
    }
    
    a{
        color: white;
        font-size: 20px;
        height: 100%;
        display: flex;
        align-items: center;
        
    }

    .nav__link{
        transition: 0.5s;
    }
    .nav__link:hover{
        color: black;
        background-color: white;
    }
</style>