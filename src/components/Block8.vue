<template>
<div class="reasons_block">
    <div class="reasons">
        <div class="reas">
            <p class="reasons_title">There are many reasons to get down</p>
        </div>
        
        <p class="reasons_text">There are many reasons to get<br /> down and start to get depressed about your situation.</p>
         <b-field class="email">
            <b-input class="email_field" placeholder="Your email" type="search"></b-input>
            <div class="control">
                <p class="but text_but">SEND</p>
            </div>
        </b-field>
        <p class="desc">No spam. Only releases, updates and discounts</p>
        
    </div>
</div>
    
</template>

<style>
    .reas{
       padding-top: 58px;
    }
    .desc{
        margin-left: 312px;
        height: 20px;
        left: 12.02%;
        right: 12.26%;
        top: calc(50% - 20px/2 + 36px);

        font-family: Gilroy-SemiBold;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */

        letter-spacing: 0.2px;

        /* T1 */

        color: #2D2348;
    }
    .text_but{
        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 20px;
        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;
        color: #FFFFFF;

    }
    .but{
        padding-top: 18px;
        width: 128px;
        height: 56px;
        background: #F2994A;
        border-radius: 0px 5px 5px 0px;
    }
    .email_field{
        background: #F6F6F6;
        opacity: 0.1;
        border-radius: 5px;
        width: 308px;
        height: 56px;
    }
    .email{
        margin-top: 23px;
        margin-left: 262px;
        margin-right: 262px;
    }
    .reasons_text{
        height: 44px;
        font-family: Rubik;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 22px;
        text-align: center;
        color: #95A1BB;
        margin-top: 20px;
    }
    .reasons_title{
       
        height: 43px;
        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 36px;
        line-height: 43px;
        text-align: center;
        color: #F2994A;
        

    }

    .reasons_block{
        padding: 200px 545px 168px 200px;
       
    }

    .reasons{
        height: 324px;
        width: 940px;
        background: rgba(60, 62, 125, 0.19);
        backdrop-filter: blur(134px);
        border-radius: 5px;
        
       
    }

    @font-face {
        font-family: 'Rubik';
        src: local('Rubik-v14-latin-regular'), local('Rubik-v14-latin-regular'),
            url('/../font/Rubik-v14-latin-regular.ttf') format('truetype');
        font-weight: 600;
        font-style: normal;
    }

     @media screen and (max-width: 1024px){
        .reasons_block {
            padding: 200px 545px 168px 50px;
        }
     @media screen and (max-width: 768px) {
          .reasons_block {
            padding: 200px 545px 168px 0px;
        }

        .reasons {
        width: 760px;
        }
     }
     @media screen and (max-width: 375px) {
         .reasons {
             width: 360px;
        }
        .reasons_title {
            height: 43px;
            font-family: Rubik;
            font-style: normal;
            font-weight: 500;
            font-size: 36px;
            line-height: 23px;
            text-align: center;
            color: #F2994A;
        }
     }
    
}
    

</style>