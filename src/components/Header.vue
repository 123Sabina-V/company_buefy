<template>
<div class="navbar_ab">
    <b-navbar class="navbar_ab"
    
    text-center
    >
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img class="logo" src="/../img/Logo.png">
            </b-navbar-item>
        </template>
        <template #start>
            
            <b-navbar-item href="#">
               <p class="head_font"> ABOUT</p>
            </b-navbar-item>
            <b-navbar-item href="#">
                <p class="head_font"> GALLERY</p>
            </b-navbar-item>
            <b-navbar-item href="#">
                <p class="head_font"> PRICING</p>
            </b-navbar-item>
            <b-navbar-item href="#">
                <p class="head_font"> FAQ</p>
            </b-navbar-item>
            <b-navbar-item href="#">
                <p class="head_font ben"> BENEFITS</p>
            </b-navbar-item>
            
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div >
                    <button class="buton1">
                       <p class="text_btn1">Sign in</p> 
                    </button>
                    <button class="buton2">
                        <p class="text_btn2">Sign up</p> 
                    </button>
                    
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</div>
    
</template>

<style>

    .text_btn1{
        height: 20px;
        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 20px;
        text-align: center;
        letter-spacing: 2px;
        text-transform: uppercase;
        color: rgb(219, 168, 73);
    }

    .text_btn2{
        height: 20px;
        left: 22.71%;
        right: 23.72%;
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
    .buton1{
        
        border-radius: 10px;
        width: 112px;
        height: 36px;
        border:  2px solid rgb(219, 168, 73);
       
        
        margin-right: 20px;
    }

    .buton2{
        width: 112px;
        height: 36px;
        border-radius: 10px;
        background-color: rgb(219, 168, 73);
        border:  2px solid rgb(219, 168, 73);
        margin-right: 20px;
    }
    .ben{
        margin-right: 229px;
    }
    .head_font{
       
        height: 20px;
        font-family: Gilroy-SemiBold;
        font-size: 12px;
        line-height: 20px;
        letter-spacing: 2px;
        color: #B5B5B5;

    }
    .logo{
        margin-right: 20px;
    }
    .navbar_ab{
       
        padding: 20px 130px 20px 100px;
        background-color: #2D2348;
    }
     @media screen and (max-width: 1024px){
          .navbar_ab{
              padding: 20px 130px 20px 70px;
          }
          .ben{
            margin-right: 0px;
        }
          
     }
     @media screen and (max-width: 767px) {

     }
     @media screen and (max-width: 375px) {
         .navbar_ab {
            padding: 20px 130px 20px 80px;
        }
     }
 
 
</style>