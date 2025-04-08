<template>
  <div class="home">
    
    <img class="car" src="@/assets/car.jpg">
    <div class="h1"></div>
    <div class="top"></div>
    <img class="logo" src="@/assets/logo.png">
    
  </div>
<div class="menu">
  <input name="men" type="radio" id="app" class="tap" checked>
  <label for="app">Home</label>
  
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

<input name="men" type="radio" id="Partner" class="tap">
    <router-Link to="/Partner">
    <label for="Partner">Partner</label>
  </router-Link>
  
  <input name="men" type="radio" id="Testimonials" class="tap">
    <router-Link to="/Testimonials">
    <label for="Testimonials">Testimonials</label>
  </router-Link>
  
</div>

<div class="conteaner">
  dir='rtl'
lang='ar'

<p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:65em; top:0.5em; cursor: pointer;">اللغة العربية</p>
</div>


<button id="log-btn" >log in</button>
<div class="text">
<h3> safe & Reliable Logistic 
  Solution</h3>

  <div class="tex">
    <h6>KNAGER is App Of Logistic Services For Drop shipping Sector.</h6>
  </div>
</div>



<input class="box-text" placeholder=" Enter Your Order ID  " style="color:#000">


<button id="track-btn" >Track</button>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>


<style lang="scss">
.car{
left:0em;
top:0em;
position: absolute;
width: 100%;
height: 100%;
}

.top{
  position: absolute;
  left: -60vh;
  top: -13px;
  background: #ffffff;
  height:70px;
width:129.5%;
opacity:3;

}

.h1{
  position: absolute;
bottom: 100;
background: rgba(0,0,0,0.5);
color: white;
width: 96.6%;
height: 93.2%;
top:0;
left:0em;
padding:20px;

}

.logo{
  position: absolute;
left:9em;
 width: 90px;
 top:0em;

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

.text{
  position: absolute;
  color: #FAFAFA;
  top:3em;
  font-size: 35px;
  text-align: left;
  width: 500px;
  left:3em;
  top:4em;
 font-family:'Poppins';
}

.tex{
  position: absolute;
  color: #FAFAFA;
  font-size: 20px;
  left:0em;
  top:7em; 
  width: 350px;
  
}



/*box*/
.box-text{
  color: #FAFAFA;
  position: absolute;
  width: 350px;
  height: 40px;
  border-radius: 9.69444px;
  border: none;
left:7.5em;
  top:27.5em;

}

#track-btn {

position: absolute;
width: 80px;
height: 40px;
left: 29em;
background-color: #F5AC01;
border-radius: 7px;
font-family: 'Poppins';
padding-top: 10px;
padding-bottom: 10px;
font-weight: 500;
font-size: 16px;
border-color: #F5AC01;
border: none;
color: #FFFFFF;
top:23em;
}
</style>