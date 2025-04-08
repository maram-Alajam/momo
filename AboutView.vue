<template>
        
  <div class="about">

    <img class="photo" src="@/assets/repository.png">
    <img class="sq" src="@/assets/square.png">
      
      <div class="top"></div>
      <img class="logo" src="@/assets/logo.png">
      
    </div>
  
  
    <div class="menu">
  <input name="men" type="radio" id="home" class="tap" >
  <router-Link to="/main">
  <label for="home">Home</label>
</router-Link>
  <input name="men" type="radio" id="About" class="tap" checked>
 
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
  <div class=" text1">
  About Us
</div>

<div class="text22">
  WE ARE KNAGER
</div>
<img class="line" src="@/assets/line.png">

<div class="text3">
    An Electronic Platform Established in 2017
    That Seeks To Be The First Platform in
     Logistics Services And The Leader In Delivery
     And Freight Services Through A Wide
     Network Of Companies And Individuals And
     A Fleet Of Drivers Available Around The 
     Clock Throughout The Region
  </div>
  </template>
  
 
  
  
  <style>
.photo{
left:0em;
top:0em;
position: absolute;
width: 100%;
height: 100%;
}

.sq{
  position: absolute;
width: 600px;
height: 500px;
left: 276px;
top:5em;

background: rgba(0, 0, 0, 0.7);
}
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
  
  .text1{
    color: #c0bebe;
    position: absolute;
    top:6em;
    left:16.7em;
    font-size: 19px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .text22{
    color: #FFFFFF;
    position: absolute;
   left:12.5em; 
   font-size: 25px;
   top:6.5em;
   font-weight: bold;
  }

  .line{
    position: absolute;
    top:13em;
    left:20em;
    width: 80px;
  }

  .text3{
    position: absolute;
    top:17em;
    color: #FFFFFF;
    width: 400px;
    font-size: 16px;
    left:20em;
    text-align: left;
    padding-top: 2px;
    font-weight: lighter;
    line-height: 35px;
    word-spacing: 2px;
  }
  </style>
  