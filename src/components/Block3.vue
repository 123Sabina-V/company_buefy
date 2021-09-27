<template>
    <div class="wrapper4">
        <div class="incr">
            <h5 class="tit_incr">Increase your<br /> business <span class="traf">traffic</span></h5>
            <p class="p_incr">We are committed to processing the information in order to<br /> contact you and talk about your project. </p>
            <button class="button1">
                <p class="btn_1">Learn More</p> 
            </button>
        </div>
        <div class="overview">
            <img src="/../img/Image.png" alt="">

        </div>
    </div>
</template>

<style scoped>
    .p_incr{
        height: 56px;
        font-family: Gilroy-Semibold;
        font-size: 15px;
        line-height: 28px;
        letter-spacing: 0.5px;
        color: #8476AA;
        margin-bottom: 43px;
        
    }
    .wrapper4{
        display: grid;
        grid-template-columns: 470px 441px;
        padding: 130px 222px 150px 251px;
    }

    .traf{
        color: #F2994A;
    }

    .tit_incr{
            
            font-family: Inter;
            font-style: normal;
            font-weight: bold;
            font-size: 42px;
            line-height: 50px;
            color: #99EFD0;
            margin-bottom: 32px;

    }

    @font-face {
    font-family: 'Gilroy';
    src: local('/../font/Gilroy Semibold'), local('Gilroy-Semibold'),
        url('/../font/Gilroy-Semibold.woff2') format('woff2'),
        url('/../font/Gilroy-Semibold.woff') format('woff'),
        url('/../font/Gilroy-Semibold.ttf') format('truetype');
    font-weight: 600;
    font-style: normal;
  }
  @font-face {
    font-family: 'Inter';
    src: local('/../font/Inter Bold'), local('Inter-Bold'),
        url('/../font/Inter-Bold.ttf') format('truetype');
    font-weight: 600;
    font-style: normal;
  }

  @media screen and (max-width: 1024px){
        .wrapper4 {
        display: grid;
        grid-template-columns: 370px 341px;
        padding: 130px 222px 0px 51px;
     }
  }
     @media screen and (max-width: 767px) {

     }
     @media screen and (max-width: 500px) {

     }
 
</style>