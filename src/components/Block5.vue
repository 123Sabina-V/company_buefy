<template>
    <div class="created">
        <h7 class="created">Create your next project with startup <br /><span class="traf">framework</span></h7>
        <div class="container">
            <img src="/../img/Framer.png" alt="">
            <p class="btn text_btn">GET STARTED</p>
        </div>
        
       
        
    </div>
</template>

<style>
    .created{
        margin-top: 169px;
        text-align: center;
        font-family: Inter;
        font-style: normal;
        font-weight: bold;
        font-size: 42px;
        line-height: 50px;
        text-align: center;
        color: #99EFD0;
    }
    .text_btn{
        
        font-family: Rubik;
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        line-height: 20px;
        text-align: center;
        
    }
    

    .container {
  position: relative;
  width: 50%;
}

/* Make the image responsive */
.container img {
  width: 100%;
  height: auto;
}

/* Style the button and place it in the middle of the container/image */
.container .btn{
    height: 54px;
    width: 164px;
    border-radius: 3px;

  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  background-color: #F2994A;
  color: white;
  font-size: 16px;
  padding: 12px 24px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
}

.container .btn:hover {
  background-color: black;
}

@font-face {
        font-family: 'Rubik';
        src: local('Rubik-v14-latin-regular'), local('Rubik-v14-latin-regular'),
            url('/../font/Rubik-v14-latin-regular.ttf') format('truetype');
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