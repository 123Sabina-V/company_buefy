<template>
    <div class="blockk">
        <div class="sha">
            <div>
                <p class="shakir">ARShakir</p>
            </div>
            <div>
                 <img src="/../img/Social.png" alt="">
            </div>
        </div>
        <div class="foot_desc">
            <div>
                <p class="foot_fir">First</p>
                <p class="foot_page">First page</p>   
                <p class="foot_page">Second page</p> 
                <p class="foot_page">Third page</p>
                <p class="foot_page">Fourth page</p>
            </div>
            <div>
                <p class="foot_fir">Second</p>
                <p class="foot_page">First page</p>   
                <p class="foot_page">Second page</p> 
                <p class="foot_page">Third page</p>
                <p class="foot_page">Fourth page</p>
            </div>
            <div>
                <p class="foot_fir">Third</p>
                <p class="foot_page">First page</p>   
                <p class="foot_page">Second page</p> 
                <p class="foot_page">Third page</p>
                <p class="foot_page">Fourth page</p>
            </div>
            <div>
                <p class="foot_fir">Fourth</p>
                <p class="foot_page">First page</p>   
                <p class="foot_page">Second page</p> 
                <p class="foot_page">Third page</p>
                <p class="foot_page">Fourth page</p>
            </div>
            
        </div>
    
    </div>
</template>

<style>
    .foot_page{
        height: 20px;
        font-family: Inter;
        font-style: normal;
        font-weight: normal;
        font-size: 15px;
        line-height: 20px;
        letter-spacing: 0.2px;
        color: #FFFFFF;
    }
    .foot_fir{
        height: 18px;
        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 15px;
        line-height: 18px;
        letter-spacing: 0.2px;

        color: #FFFFFF;
    }
    .copy{
        padding-right: 256px;
    }
    .fdesc{
        display: grid;
        grid-template-columns: 160px 160px 160px;
        
    }
    .foot_desc{
        display: grid;
        grid-template-columns: 256px 256px 256px 256px;
        margin-bottom: 120px;
    }
    .sha{
        display: grid;
        grid-template-columns: 680px 152px;
        margin-bottom: 94px;
    }
    .blockk{
        padding: 46px 303px 58px 303px;
    }

    .shakir{
        
        width: 480px;
        height: 32px;
        left: 200px;
        top: 4885px;

        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 26px;
        line-height: 32px;
        /* identical to box height, or 123% */

        letter-spacing: 0.325px;

        /* Base */

        color: #F2994A;
    }

    @font-face {
    font-family: 'Inter';
    src: local('/../font/Inter Regular'), local('Inter-Regular'),
        url('/../font/Inter-Regular.ttf') format('truetype');
    font-weight: 600;
    font-style: normal;
  }
    @media screen and (max-width: 1024px){
        .blockk {
        padding: 46px 303px 58px 50px;
        }
     @media screen and (max-width: 768px) {
         .sha {
            display: grid;
            grid-template-columns: 480px 152px;
            margin-bottom: 94px;
        }
     }
     @media screen and (max-width: 500px) {

     }
    
}
  
</style>