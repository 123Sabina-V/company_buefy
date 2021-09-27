<template>
    <div class="simplep">
        <h7 class="fonts">3 Simple Ways To <span class="traf">Save</span> A Bunch<br /> Of <span class="traf">Money</span> When Buying A New Computer</h7>
        <p class="p_simple">Fully customizable and neatly organized components<br /> will help you work faster without limiting creative freedom.</p>
        <div class="wrapper_simp">
            <div>
                <p class="p_100">100+</p>
                <p class="reasonss">5 Reasons To Purchase<br /> Desktop Computers</p>
            </div>
            <div>
                <p class="p_100">43,000+</p>
                <p class="reasonss">3 Simple Ways To Save A Bunch Of<br /> Money When Buying A New Computer</p>
            </div>
            <div>
                <p class="p_100">30+</p>
                <p class="reasonss">A Discount Toner Cartridge<br /> Is Better Than Ever And You<br /> Will Save 50 Or More</p>
            </div>
           
        </div>
    </div>
</template>

<style>

    .reasonss{
        margin-top: 16px;
        height: 60px;
        font-family: Gilroy-SemiBold;
        font-size: 15px;
        line-height: 20px;
        text-align: center;
        letter-spacing: 0.2px;
        
    }

    .p_100{
        height: 42px;
        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 36px;
        line-height: 42px;
        text-align: center;
        letter-spacing: 0.33px;
        color: #99EFD0;
    }
    .wrapper_simp{
        display: grid;
        grid-template-columns: 291px 291px 291px;

    }
    .p_simple{
        margin-top: 32px;
        margin-bottom: 48px;
       
       

        font-family: Gilroy-SemiBold;
        font-size: 15px;
        line-height: 20px;
        /* or 133% */

        text-align: center;
        letter-spacing: 0.2px;

        /* T1 */

       
    }
    .fonts{
        
        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 36px;
        line-height: 42px;
        text-align: center;
        letter-spacing: 0.33px;
        color: #99EFD0;
        
    }

    .simplep{
        padding: 46px 288px 32px 288px;
        background-color: #2D2348;
    }

    .traf{
        color: #F2994A;
    }
    @font-face {
        font-family: 'Gilroy';
        src: local('/../font/Gilroy-Semibold'), local('Gilroy-Semibold'),
            url('/../font/Gilroy-SemiBold.woff2') format('woff2'),
            url('/../font/Gilroy-Semibold.woff') format('woff'),
            url('/../font/Gilroy-Semibold.ttf') format('truetype');
        font-weight: 600;
        font-style: normal;
    }
    @font-face {
        font-family: 'Inter';
        src: local('/../font/Inter'), local('Inter'),
            url('/../font/Inter.ttf') format('truetype');
        font-weight: 600;
        font-style: normal;
    }
</style>