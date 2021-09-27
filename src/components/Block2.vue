<template>
    <div class="block3">
        <h1 class="choice">Your choice</h1>
        <p class="subtitle_choice">There are many reasons to get down and start to get depressed about your situation. </p>
        <div class="wrapper3">
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/Flip-horizontal.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Ecstatic elegance</h2>
                    <p class="p_art">Article nor prepare chicken you him<br /> now. Shy merits say advice ten before lovers innate add.</p>
                </div>
            </div>
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/Airpods.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Folly words widow</h2>
                    <p class="p_art">Effect if in up no depend seemed.<br /> Ecstatic elegance gay but disposed.<br /> We me rent been part what.</p>
                </div>
            </div>
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/LTE.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Possible procured trifling</h2>
                    <p class="p_art">We me rent been part what. An <br />concluded sportsman offending so provision mr education.</p>
                </div>
            </div>
        </div>
        <div class="wrapper3">
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/Thunder-move.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Open game</h2>
                    <p class="p_art">Shy merits say advice ten before<br /> lovers innate add. She cordially<br /> behaviour can attempted estimable.</p>
                </div>
            </div>
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/Attachment.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Endeavor</h2>
                    <p class="p_art">Improve ashamed married expense<br /> bed her comfort pursuit mrs. Four time<br /> took ye your as fail lady. </p>
                </div>
            </div>
            <div class="es_wrapper">
                <div><img class="img_ecs" src="/../img/Bulb.png" alt=""></div>
                <div>
                    <h2 class="h_ecs">Comfort pursuit</h2>
                    <p class="p_art">Had denoting properly jointure you<br /> occasion directly raillery. In said to of<br /> poor full be post face snug.</p>
                </div>
            </div>
        </div>  
        </div>
   
</template>

<style>
    .p_art{
        width: 247px;
        height: 66px;
        font-family: Gilroy-SemiBold;
        font-size: 14px;
        line-height: 22px;
        color: #8476AA;
    }

    .h_ecs{
        width: 218px;
        height: 22px;
        font-family: Gilroy-SemiBold;
        font-size: 18px;
        line-height: 22px;
        color: #99EFD0;
    }
   
    .es_wrapper{
        display: grid;
        grid-row: 2;
        grid-template-columns: 52px 257px;
        padding: 50px 286px 15px 254px;
    }
    .block3{
        background-color: #2D2348;
    }

    .choice{
        margin-top: 120px;
        font-family: Inter-Bold;
        font-style: normal;
        font-weight: bold;
        font-size: 42px;
        line-height: 50px;
        text-align: center;
        color: #99EFD0;
    }

    .subtitle_choice{
        margin-top:13px;
        height: 22px;
        font-family: Gilroy-SemiBold;
        font-size: 16px;
        line-height: 22px;
        text-align: center;
        color: #8476AA;
    }

    .wrapper3{
        grid-row: 2;
        display: grid;
        grid-template-columns: 299px 299px 299px;
    }
@font-face {
    font-family: 'Gilroy';
    src: local('/../font/Gilroy-SemiBold'), local('Gilroy-Semibold'),
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

  @media screen and (max-width: 1366px){
      .es_wrapper {
            display: grid;
            grid-row: 2;
            grid-template-columns: 32px 257px;
            padding: 50px 0px 15px 50px;
        }
  }

    @media screen and (max-width: 1024px){
        .es_wrapper {
            display: grid;
            grid-row: 2;
            grid-template-columns: 32px 257px;
            padding: 50px 0px 15px 120px;
        }
         .wrapper3 {
            display: grid;
            grid-template-columns: 250px 250px 199px;
            
        }
          
     }
     @media screen and (max-width: 768px) {
         .wrapper3 {
            display: grid;
            grid-template-columns: 250px 250px 199px;
            
        }
        .es_wrapper {
            display: grid;
            grid-row: 2;
            grid-template-columns: 32px 240px;
            padding: 50px 0px 15px 0px;
        }
     }
     @media screen and (max-width: 375px) {
         .wrapper3 {
            display: grid;
            grid-template-columns: 300px;
            margin-left: 90px;
         }
     }
 
</style>