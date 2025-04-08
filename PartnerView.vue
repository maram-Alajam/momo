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
  <input name="men" type="radio" id="About" class="tap">
  <router-Link to="/about">
  <label for="about">About Us</label>
  </router-Link>
  
  <input name="men"  type="radio" id="Features" class="tap">
  <router-Link to="/features">
  <label for="Features">Features</label>
</router-Link>
  <input name="men" type="radio" id="Services" class="tap">
  <router-Link to="/services">
  <label for="Services">Services</label>
</router-Link>
  <input name="men" type="radio" id="Partner" class="tap" checked>
    
    <label for="Partner">Partner</label>

  
  <input name="men" type="radio" id="Testimonials" class="tap">
    <router-Link to="/testimonials">
    <label for="Testimonials">Testimonials</label>
  </router-Link>
  

</div>
    
    <div class="conteaner">
    
    
    <p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:65em; top:0.5em; cursor: pointer;">اللغة العربية</p>
    </div>
    
    
    <button id="log-btn" >log in</button>


    <div class="tx1">
      OUR AWESOME PARTNER
    </div>

    <img class="line4" src="@/assets/line4.svg">
   
   

    
    <Carousel :breakpoints="breakpoints">
      
    <Slide v-for="slide in 10" :key="slide">
      <img class="carousel__item" src="@/assets/kw1.svg" >
    </Slide>

    <template #addons>
      <Navigation />
    </template>
  </Carousel>


    <div class="line5"></div>
    <div class="line6"></div>
    <div class="te">
      DO YOU WANT TO INCREASE YOUR INCOME BY JOINNING KANGER?
    </div>

    <div class="to1">
    Unlimited Reception Of Requests
</div>

<div class="to2">
 Requests From Stores And Individuals
</div>

<div class="to3">
Sort As Per Your Wish Accurate Delivery Confirmation
</div>

<div class="to4">
Rewarding Profits For Each Request
</div>

<div class="to5">
Arrived The Order With Your Car Or Bike
</div>

<div class="to6">
  Branch Delivery Support
</div>

<div class="to7">
100% Advance Payment
</div>

<img alt="ph" class="ph" src="@/assets/ph.svg">
<img alt="ph3" class="ph3" src="@/assets/ph3.svg">
<img alt="ph2" class="ph2" src="@/assets/ph2.svg">

<img class="black2" src="@/assets/black2.svg">
<img class="black" src="@/assets/black.svg">

<div class="R">
LINK YOUR ONLINE STORE OR FACILTIES NOW WITH KNAGER
</div>

<div class="R1">
AND ADD EXPRESS DELIVERY SERVICE TO THE GROWTH AND DEVELOPMENT OF YOUR BUSINESS 
</div>

<button id="order" >Order A Caption Now</button>

<img class="star" src="@/assets/star.svg">
<img class="star2" src="@/assets/star2.svg">
<img class="star3" src="@/assets/star3.svg">
<img class="star4" src="@/assets/star4.svg">
<img class="star5" src="@/assets/star5.svg">
<img class="star6" src="@/assets/star6.svg">
<img class="star7" src="@/assets/star7.svg">
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
        snapAlign: 'center',
      },
      // 1024 and up
      1024: {
        itemsToShow: 5,
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
     background-color: #FAFAFA;
    
    }
    
    /* menu*/
    
    .menu{
      position:absolute;
      left:19em;
      padding: 8px;
      cursor: pointer;
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
    
    }

    a:link{
    text-decoration: none;
  }
    
    input:checked +label{
      background-color: #F5AC01;
      color: #FAFAFA;
      
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
  
    .tx1{
      color:black;
      position: absolute;
      font-weight: bolder;
      top:5em;
      left:4em;
      font-size: larger;

    }
    
    .line4{
      position: absolute;
      top:8em;
      left:5em;
      width: 55px;
    }

    .kw1{
      position: absolute;
      top:11em;
      left:5em;
      width: 165px;
      
    }

    

    .line5{
      position: absolute;
      background: #D9D9D9;
      transform: rotate(-180deg);
      width: 450px;
      height: 1px;
      left:5em;
      top:25em;
    }

    .line6{
      position: absolute;
      background: #D9D9D9;
      transform: rotate(-180deg);
      width: 450px;
      height: 1px;
      left:62em;
      top:25em;
    }

    .carousel__item {
  min-height: 200px;
  width: 80%;
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
 margin-top:6em;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev{
 left:17.6em;
  border-radius: 9.5559px;
  background-color: #F5AC01;
  color:#FAFAFA;
  box-sizing: content-box;
  position: absolute;
  top:13.1em;
  width: 25px;
}
.carousel__next {
  box-sizing: content-box;
top:-5.9em;
width: 25px;
position: absolute;
margin:570px;
right: 1em;
  border-radius: 9.5559px;
  background-color: #F5AC01;
  color:#FAFAFA;
}

.te{
  position: absolute;
  left:25em;
  top:23em;
  font-size: 20px;
 width: 500px;
 text-align: left;
font-weight: bold;
color:black;
}
.to1{
    position: absolute;
    top: 33em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to2{
    position: absolute;
    top: 36.3em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to3{
    position: absolute;
    top: 40em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to4{
    position: absolute;
    top: 43.5em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to5{
    position: absolute;
    top: 47em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to6{
    position: absolute;
    top: 50em;
    left: 33em;
    color: rgba(104, 104, 104, 1);
  }

  .to7{
    position: absolute;
    top: 53em;
    left: 33em;
    color: rgba(104, 104,104,1);
}


.ph{
width: 350px;
position: absolute;
left: 5em;
top: 29em;

}

.ph3{
width: 210px;
position: absolute;
left: 8.5em;
top: 27em;

}

.ph2{
width: 180px;
position: absolute;
left:9.5em;
top: 28.3em;
border-radius:9.69444px;

}

.black2{
  position: absolute;
  top: 56em;
  width: 100%;
  left: 0em;
}

.black{
  position: absolute;
  top: 56em;
  width: 100%;
  left: 0em;
}

.R{
  position: absolute;
  top: 48em;
color: #FAFAFA;  
left: 15em;

font-size: 20px;
}

.R1{
  position: absolute;
  top: 68em;
color: #FAFAFA;  
left: 15em;
font-size: 15px;
}

#order {
  box-sizing: border-box;
  position: absolute;
  width: 220px;
  height: 50px;
  left: 26em;
  background: rgba(245, 172, 1, 1);
  border-radius: 9.69444px;
  border: none;
  font-size: 18px;
  color: #FFFFFF;
top:60em;
}

.star{
    position: absolute;
    top: 33em;
    width: 20px;
    left: 31em;
  }

  .star2{
    position: absolute;
    top: 36.3em;
    width: 20px;
    left: 31em;
  }
  .star3{
    position: absolute;
    top: 40em;
    width: 20px;
    left: 31em;
  }
  .star4{
    position: absolute;
    top: 43.5em;
    width: 20px;
    left: 31em;
  }
  .star5{
    position: absolute;
    top: 47em;
    width: 20px;
    left: 31em;
  }
  .star6{
    position: absolute;
    top: 50em;
    width: 20px;
    left: 31em;
  }
  .star7{
    position: absolute;
    top: 53em;
    width: 20px;
   left:31em;
}
   </style>