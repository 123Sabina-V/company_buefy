<template>

    <div class="wrapper">
        <div class="block1">
            <h1 class="text_block1">Many reasons to get up <br /> and start to get back in <br />the business</h1>
            <p class="subtitle">The harder you work for something, the greater you’ll<br /> feel when you achieve it.</p>
            <div>
                <button class="button1">
                    <p class="btn_1">Learn More</p> 
                </button>
                <button class="button2">
                    <p class="btn_2">Demo</p> 
                </button>
            </div>
            <div class="wrapper2">
            <div class="bl_pic"><img src="/../img/Picture.png" alt=""></div>
            <div class="bl_text">
                <p class="bl_title">The harder you work for something, the greater<br /> you’ll feel when you achieve it.</p>
                <p class="bl_subtitle">Watch preview</p>
            </div>
        </div>
            
        </div>
    
        <div class="block2"><img src="/../img/Frame.png" alt=""></div>
    
    </div>

    
</template>

<style>

    .bl_pic{
        margin-right: 20px;
    }
    .bl_title{
        height: 44px;
        

        /* Paragraph */

        font-family: Rubik;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 22px;
        /* or 137% */


        /* T1 */

        color: #8476AA;
    }

    .bl_subtitle{
        height: 22px;
        left: 29.63%;
        right: 52.78%;
        top: calc(50% - 22px/2 + 25px);

        /* Small Paragraph */

        font-family: Rubik;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 22px;
        /* identical to box height, or 157% */


        /* Neutral 4 */

        color: #6D6D78;
    }
    .wrapper2{
        margin-top: 60px;
        display: grid;
        grid-template-columns: 140px 400px;
        
    
    }
    .block1{
        padding:100px 0px 12px 170px;
        
       
    }

    .block2{
        margin-left: 100px;
        
    }

    .text_block1{
        
        width: 521px;
        height: 150px;
        left: 180px;
        top: 250px;

        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 44px;
        line-height: 50px;
        /* or 114% */


        /* T2 */

        color: #99EFD0;
        margin-bottom: 15px;
    }

    .subtitle{
        
        width: 468px;
        height: 44px;
        left: 170px;
        top: 419px;

        font-family: Gilroy-SemiBold;
        font-size: 18px;
        line-height: 22px;
        /* or 122% */


        /* T1 */

        color: #8476AA;
        
    }
    .wrapper{
        display: grid;
        grid-template-columns: 540px 724px;
    }

    .button1{
        width: 157px;
        height: 46px;
        border-radius: 10px;
        background-color: rgb(219, 168, 73);
        color: black;
        margin-right: 20px;
    }

    .button2{
        width: 157px;
        height: 46px;
        border-radius: 10px;
        background-color: #2D2348;
        color: black;
        border:  2px solid rgb(219, 168, 73);
        
    }

    .btn_1{
        height: 20px;
        left: 19.79%;
        right: 20.34%;
        top: calc(50% - 20px/2);

        /* Link */

        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 20px;
        /* identical to box height, or 167% */

        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;

        color: #FFFFFF;

    }

    .btn_2{
        height: 20px;
        left: 36.69%;
        right: 37.83%;
        top: calc(50% - 20px/2);

        /* Link */

        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 20px;
        /* identical to box height, or 167% */

        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;

        /* Base */

        color: #F2994A;
    }

      @media screen and (max-width: 1024px){
         .block1 {
            padding: 100px 0px 12px 100px;
        }
        .wrapper {
            display: grid;
            grid-template-columns: 540px 624px;
        }
        .block2 {
            margin-left: 100px;
            margin-top: 80px;
        }
          
     }
     @media screen and (max-width: 768px) {
         .text_block1 {
            font-size: 24px;
        }
        .block1 {
            padding: 50px 0px 12px 100px;
        }

        .wrapper {
            display: grid;
            grid-template-columns: 340px 524px;
        }
        .button1{
            margin-bottom: 20px;
        }
     }
     @media screen and (max-width: 375px) {
         .block1 {
            padding: 50px 0px 12px 50px;
        }

        .subtitle{
            width: 300px;
            margin-bottom: 12px;
        }
        .button1 {
            margin-top: 20px;
        }

        .bl_title{
            width: 200px;
        }
     }
</style>