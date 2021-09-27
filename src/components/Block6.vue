<template>
    <div class="wrapper_6">
        <div class="wrap_1">
            <p class="investf">Invest property for better <span class="traf">business</span></p>
            <p class="commit">We are committed to processing the information in order to contact you and talk about your project. We are committed to processing the information.</p>
            <button class="button1">
                <p class="btn_1">Learn More</p> 
            </button>
        </div>

        <div class="wrap_2">
            <img src="/../img/Group6.png" alt="">
        </div>
    

    </div>
</template>

<style>
    .commit{
        margin-bottom: 46px;
    }
    .investf{
        margin-bottom: 32px;
        height: 100px;
        left: 17.41%;
        right: 50%;
        top: calc(50% - 100px/2 - 109px);

        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 42px;
        line-height: 50px;
        /* or 119% */


        /* T2 */

        color: #99EFD0;
    }
    .wrapper_6{
        display: grid;
        grid-template-columns: 470px 403px;
        padding: 48px 308px 143px 251px;
    }
    .wrap_1{

    }

     @media screen and (max-width: 1024px){
       .wrapper_6 {
            grid-template-columns: 370px 341px;
            padding: 48px 308px 143px 50px;
        }
        .p_incr[data-v-36336076] {
            width: 300px;
        }
    }
     @media screen and (max-width: 767px) {

     }
     @media screen and (max-width: 375px) {
        .investf{
            width: 350px;
            margin-bottom: 60px;
        }

        .commit {
            margin-bottom: 46px;
            margin-top: 20px;
            width: 200px;
        }
     }
 
</style>    