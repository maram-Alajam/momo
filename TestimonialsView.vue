<template>
        
    <div class="about">
  
    
        
        <div class="top"></div>
        <img class="logo" src="@/assets/logo.png">
        
      </div>
    
    
      <div class="menu">
    <input name="men" type="radio" id="home" class="tap" >
    <router-Link to="/main">
    <label for="home">Home</label>
  </router-Link>
    <input name="men" type="radio" id="About" class="tap" >
   
    <label for="about">About Us</label>
   
    
    <input name="men"  type="radio" id="Features" class="tap">
    <router-Link to="/features">
    <label for="Features">Features</label>
  </router-Link>
    <input name="men" type="radio" id="Services" class="tap">
    <router-Link to="/services">
    <label for="Services">Services</label>
  </router-Link>
  
  <input name="men" type="radio" id="Partner" class="tap">
    <router-Link to="/Partner">
    <label for="Partner">Partner</label>
  </router-Link>
  
  <input name="men" type="radio" id="Testimonials" class="tap"  checked>
  
    <label for="Testimonials">Testimonials</label>
  
  </div>
  <div class="conteaner">
      dir='rtl'
    lang='ar'
    
    <p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:65em; top:0.5em; cursor: pointer;">اللغة العربية</p>
    </div>
    
    
    <button id="log-btn" >log in</button>

    <div class="ttt1">

 WHAT OUR CLIENT SAY
    </div>
<img class="line7" src="@/assets/Line7.svg">


<Carousel :breakpoints="breakpoints">
      
      <Slide v-for="slide in 10" :key="slide">
        <div class="carousel__item">  LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE. 
       <img class="ali" src="@/assets/ali.svg">
       <p class="ttt3">
        Ali Ahmed
       </p>
       <p class="ttt4">
        Fashion Company
       </p>
      </div>

      </Slide>
  
      <template #addons>
        <Navigation />
      </template>
    </Carousel>


    <div class="boox">
     <div class="ttt5">
      Always Listening, Always Understanding
     </div>
     <input type="text" class="text">


     <button id="send" >Send</button>
    </div>



    <div class="orange"></div>

<img class="logot" src="@/assets/logot.svg">

<div class="t9">
  An Electronic Platform Established In 2017 That  </div>

  <div class="t10">
Seeks To Be The First Platforms In Logistics Services</div>

<div class="t11">
And The Leader In Delivery And Freight Services </div>


<img class="mar" src="@/assets/mar.svg">

<div class="t12">
Lines Company For</div>

<div class="t13">
Programming And Marketing </div>

<div class="t14">
Tax Number 34564424525252 </div>

<div class="t15">
Quick Links </div>

<img class="sh1" src="@/assets/sh1.svg">
<img class="sh2" src="@/assets/sh2.svg">
<img class="sh3" src="@/assets/sh3.svg">
<img class="sh4" src="@/assets/sh4.svg">
<img class="sh5" src="@/assets/sh5.svg">

<div class="t16">
Terms And Conditions </div>
<div class="t17">
Privacy Of Use </div>
<div class="t18">
Return Policy </div>
<div class="t19">
Business Cooperation </div>
<div class="t20">
Developers Portal </div>


<div class="t21">
Get In Touch</div>

<img class="tele" src="@/assets/tele.svg">


<div class="t22">
+972595111957 </div>

<div class="t23">
+972595111957 </div>

<div class="t24">
Saudi Arabia, Dammam </div>

<img class="sms" src="@/assets/sms.svg">
<img class="loc" src="@/assets/loc.svg">

<img class="saudi" src="@/assets/saudi.svg">
<img class="stc" src="@/assets/stc.svg">
<img class="visa" src="@/assets/visa.svg">

<img class="e" src="@/assets/e.svg">
<img class="e1" src="@/assets/e1.svg">
<img class="e2" src="@/assets/e2.svg">

<img class="e3" src="@/assets/e3.svg">
<img class="e4" src="@/assets/e4.svg">
<img class="e5" src="@/assets/e5.svg">
</template>


<script lang="ts">
  
import { defineComponent } from 'vue'
import { Carousel, Navigation, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
name: 'BreakPoints',
components: {
  Carousel,
  Slide,
  Navigation,
},
data: () => ({
  // carousel settings

  // breakpoints are mobile first
  // any settings not specified will fallback to the carousel settings
  breakpoints: {
    // 700px and up
    700: {
      itemsToShow: 2.5,
      snapAlign: 'left',
    },
    // 1024 and up
    1024: {
      itemsToShow: 1,
      snapAlign: 'start',
    },
  },
}),
})
</script>
  

  <style>
    .top{
    position: absolute;
    left: -60vh;
    top: -13px;
    background: #FAFAFA;
    height:70px;
  width:129.5%;
  opacity:3;
  
  }
  
  .logo{
    position: absolute;
  left:7em;
   width: 90px;
   top:0em;
  
  }
  
  /* menu*/
  
  .menu{
    position:absolute;
    left:19em;
    padding: 8px;
   
  }
  
  label{
   position: relative;
   color: #353535;
   font-family: 'Poppins';
   font-weight: bold;
   font-size: 16px;
   padding-bottom:  19px;
   padding-left: 19px;
   padding-top: 17px;
   padding-right: 10px;
   cursor: pointer;
    text-decoration: none;
  }
  
  input:checked +label{
    background-color: #F5AC01;
    color: #FAFAFA;
    

  }

  a:link{
    text-decoration: none;
  }

  .tap{
    display: none;
  }
  .hi{
    position: absolute;
  }
  
  #log-btn {
  
    position: absolute;
    width: 80px;
    height: 40px;
    left: 65em;
    background-color: #F5AC01;
    border-radius: 7px;
    font-family: 'Poppins';
  
    font-weight: 500;
    font-size: 16px;
   border-color: #F5AC01;
   border: none;
    color: #FFFFFF;
    top:0.5em;
  }

  .ttt1{
    color: black;
    font-weight: bold;
    position: absolute;
    left:4em;
    top:6em;

  }

  .line7{
    position: absolute;
    left:4em;
    top:7.5em;
    width: 50px;
  }

  .carousel__item {
  min-height: 200px;
  width: 80%;
  font-size: 16px;
  border-radius: 8px;
  display: flex;
  color: #535151;
left:1em;
text-align: left;
  align-items: left;
 margin-top:8em;
 margin-left: -9em;
 
 top:6em;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev{
 left:11em;
  border-radius: 8.5599px;
  background-color: #F5AC01;
  color:#FAFAFA;
  box-sizing: content-box;
  position: absolute;
  top:11em;
  width: 20px;
  height: 25px;
}
.carousel__next {
  box-sizing: content-box;
top:-8.10em;
width: 20px;
height: 25px;
position: absolute;
margin:570px;
right:15em;
  border-radius: 9.5559px;
  background-color: #F5AC01;
  color:#FAFAFA;
}


.ttt2{
  position: absolute;
  color: rgb(129, 126, 126);
}


.ali{
  position: absolute;
  top:13em;
  height: 50px;
 
}

.ttt3{
  position: absolute;
  top:12.5em;
  left:9em;

}

.ttt4{
  position: absolute;
  left:9em;
  top:13.9em;

}


.boox{
position: absolute;
width: 460px;
height: 310px;
left: 40em;
top: 6em;

background:#F9F9F9;
}

.text{
  color: #1b1a1a;
  position: absolute;
  width: 320px;
  height: 150px;
  border-radius: 9.69444px;
  border: none;
left:4.5em;
  top:6em;
  background:#ffffff;

}

#send {
  
  position: absolute;
  width: 300px;
  height: 40px;
  left: 5em;
  background-color: #F5AC01;
  border-radius: 7px;
  font-family: 'Poppins';

  font-weight: 500;
  font-size: 16px;
 border-color: #F5AC01;
 border: none;
  color: #FFFFFF;
  top:16em;
}

.ttt5{
  font-size:20px;
  width: 300px;
  left:3em;
  top:1em;
  position:absolute;
}




.orange{
  top: 30em;
  position: absolute;
  left: 0em;
  width: 100%;
  height: 265px;
  background-color: rgba(245, 172, 1, 1);
}


.logot{
  top: 31.5em;
  position: absolute;
  left: 6em;
  width: 90px;
}


.t9{
  top: 36.3em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t10{
  top: 37.5em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t11{
  top: 38.7em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.mar{
  top: 41.2em;
  position: absolute;
  left: 6em;
  width: 90px;
}

.t12{
  top: 48.7em;
  position: absolute;
  left: 14.7em;
  color: #FAFAFA;
  font-size: 13.5px;
}

.t13{
  top: 50em;
  font-size: 13.5px;
  position: absolute;
  left: 14.6em;
  color: #FAFAFA;
}

.t14{
  top: 52.3em;
  font-size: 13.5px;
  position: absolute;
  left: 7em;
  color: #FAFAFA;
}

.t15{
  top: 24.7em;
  font-size: 20px;
  position: absolute;
  left: 30em;
  color: #FAFAFA;
}

.sh1{
  top: 33em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh2{
  top: 35.5em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh3{
  top: 38.5em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh4{
  top: 41.4em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}

.sh5{
  top: 44em;
  position: absolute;
  left: 37.5em;
  width: 10px;
}



.t16{
  top: 37.6em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t17{
  top: 40.4em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t18{
  top: 43.9em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t19{
  top: 47.2em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.t20{
  top: 50.1em;
  font-size: 14px;
  position: absolute;
  left: 44em;
  color: #FAFAFA;
}

.tele{
  top: 38em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.t21{
  top: 24.6em;
  font-size: 20px;
  position: absolute;
  left: 47em;
  color: #FAFAFA;
}

.t22{
  top: 38.4em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}

.t23{
  top: 41em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}
.t24{
  top: 43.6em;
  font-size: 14px;
  position: absolute;
  left: 70em;
  color: #FAFAFA;
}

.sms{
  top: 41em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.loc{
  top: 43.4em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}

.saudi{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 67em;

}

.stc{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 74em;
}

.visa{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 78em;
}


.e{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 77em;
}

.e1{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 72em;
}
.e2{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 67em;
}




.e3{
  top: 49.7em;
  font-size: 14px;
  position: absolute;
  left: 77.7em;
}

.e4{
  top: 49.7em;
  font-size: 14px;
  position: absolute;
  left: 72.7em;
}
.e5{
  top: 49.8em;
  font-size: 14px;
  position: absolute;
  left:67.8em;
}
  </style>