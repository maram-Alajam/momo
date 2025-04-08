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
  
  <input name="men"  type="radio" id="Features" class="tap" checked>
 
  <label for="Features">Features</label>

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
     
    
    <p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:65em; top:0.5em; cursor: pointer;">اللغة العربية</p>
    </div>
    
    
    <button id="log-btn" >log in</button>


    <div class="t1">
  WHY CHOOSE US
</div>
<img class="line" src="@/assets/line.png">

<div class="box1">
<img class="loca" src="@/assets/loca.svg">

<div class="textbx1">
    INSIDE AND OUT SIDE THE <br>
    REGION

    <div class="box1tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
  
</div>
</div>
<div class="box2">

<img class="product-1"  src="@/assets/product-1.svg">
<div class="textbox2">
  ALL KINDS OF PRODUCT
</div>

<div class="box2tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box3"> 
  <img class="world"  src="@/assets/world.svg">
<div class="textbox3">
  FULL COVERAGE
</div>

<div class="box3tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box4"> 
  <img class="cyc"  src="@/assets/cyc.svg">
<div class="textbox4">
  DELIVERY IN LESS AN HOUR
</div>

<div class="box4tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box5">
  <img class="men"  src="@/assets/men.svg">
<div class="textbox5">
  DOOR PICKUP
</div>

<div class="box5tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
   </div>
<div class="box6">
  <img class="phone"  src="@/assets/phone.svg">
<div class="textbox6">
 ONLINE PAMENT
</div>

<div class="box6tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
    </template>
    
    
    
    <style>
    .top{
      position: absolute;
      left: -60vh;
      top: -13px;
      background: #FAFAFA;
      height:70px;
    width:129.2%;
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
    .t1{
        color:black;
        position: absolute;
        font-weight: bold;
        top:6em;
        left:1.8em;
        font-size: 18px;

    }
  
    .line{
    position: absolute;
    top:9em;
    left:2em;
    width: 80px;
  }
.box1{

  position: absolute;
  top: 11em;
  left: 7%;
  width: 370px;
height: 180px;
left:2em;
background: #F9F9F9;
}

.box2{

position: absolute;
top: 11em;
left: 7%;
width: 370px;
height: 180px;
left:27em;
background: #F9F9F9;
}

.box3{

position: absolute;
top: 11em;
left: 7%;
width: 370px;
height: 180px;
left:52em;
background: #F9F9F9;
}

.box4{

position: absolute;
top: 24em;
left: 7%;
width: 370px;
height: 180px;
left:2em;
background: #F9F9F9;
}


.box5{

position: absolute;
top: 24em;
left: 7%;
width: 370px;
height: 180px;
left:27em;
background: #F9F9F9;
}

.box6{

position: absolute;
top: 24em;
left: 7%;
width: 370px;
height: 180px;
left:52em;
background: #F9F9F9;
}


.loca{
 background-color:#F9F9F9 ;
 top:1.4em;
 left:2em;
 height: 60px;
 position: absolute;
}




.textbx1{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box1tex{
text-align: left; 
position: absolute;
color: #878787;
top:  6em;
left:0em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}



.product-1{
  position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox2{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box2tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}



.world{
  position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox3{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box3tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.cyc{
  position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox4{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box4tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.men{
  position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox5{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box5tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.phone{
  position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox6{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box6tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}
</style>