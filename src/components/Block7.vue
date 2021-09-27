<template>
    <div class="wphelp">
        <div class="wrimg">
            <img src="/../img/Group13.png" alt="">
        </div>
        <div class="wdesc">
            <p class="whelpf">Help Finding Information Online</p>
            <p class="wfully">Fully customizable and neatly organized components<br /> will help you work faster without limiting creative freedom.</p>
        
        <div class="wrapfeature">
            <div class="featureone">
                <img src="/../img/Swiss-knife.png" alt="">
                <p class="featext">Feature One</p>
                <p class="fea_text">Fully customizable and neatly organized components will help you work faster </p>
            </div>
            <div class="featureone">
                <img class="fea" src="/../img/LTE1.png" alt="">
                <p class="featext fea">Feature One</p>
                <p class="fea fea_text">Fully customizable and neatly organized components will help you work faster </p>
            </div>
        </div>
        </div>
    </div>
</template>

<style>
.fea{
    margin-left: 64px;
}
    .featext{
        margin-top: 16px;
        height: 18px;
        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 15px;
        line-height: 18px;
        letter-spacing: 0.2px;
        color: #99EFD0;
    }
    .wrapfeature{
        padding: 48px 166px 0px 85px;
        display: grid;
        grid-template-columns: 224px 280px;
    }
    .wfully{
         margin-left: 85px;
    }
    .wphelp{
        padding: 24px 160px 0px 189px;
        display: grid;
        grid-template-columns: 495px 512px;
    }
    .whelpf{
        margin-bottom: 32px;
        margin-top: 100px;
        margin-left: 85px;
        width: 480px;
        height: 32px;
        left: 768px;
        top: 3821px;

        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 26px;
        line-height: 32px;
        letter-spacing: 0.325px;
        color: #99EFD0;

    }
    @media screen and (max-width: 1366px){
    }
    @media screen and (max-width: 1024px){
        .wphelp {
        padding: 24px 160px 0px 0px;
        display: grid;
        grid-template-columns: 395px 512px;
    }
        .whelpf {
        margin-left: 30px;
    }

        .wfully{
            margin-left: 30px;
        }
        .wrapfeature {
        padding: 48px 166px 0px 30px;
        }

        .fea {
        margin-left: 24px;
        }
     @media screen and (max-width: 768px) {
         .es_wrapper {
            display: grid;
            grid-row: 2;
            grid-template-columns: 32px 257px;
            padding: 50px 0px 15px 0px;
        }

        .whelpf {
        margin-left: 0px;
        font-size: 20px;
        margin-bottom: 12px;
    }

        .wfully{
            margin-left: 0px;
            width: 350px;
        }

        .wrapfeature {
            padding: 28px 166px 0px 0px;
        }

        .fea_text{
            width: 130px;
        }

       
     }
     @media screen and (max-width: 500px) {

     }
    
}
</style>