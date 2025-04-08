<template>
        
    <div class="serv">
      <div class="top"></div>
      <div class="back"></div>
        
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
  <input name="men" type="radio" id="Services" class="tap" checked>
 
  <label for="Services">Services</label>

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
    <div class="tex1">
      MULTIPLE JOBS AND MORE
    </div>
    <img class="line-3" src="@/assets/Line-3.svg">

    <img class="rest" src="@/assets/restaurant.svg">
    <div class="tt1">Restaurants</div>

    <img class="sched" src="@/assets/schedule.svg">
    <img class="sched1" src="@/assets/schedule1.svg">
    <div class="tt2">Scheduling</div>
    <img class="food1" src="@/assets/food.svg">
    <img class="food2" src="@/assets/food1.svg">
    <div class="tt3">Food</div>


    <img class="eco1" src="@/assets/eco1.svg">
    <img class="eco2" src="@/assets/eco2.svg">
    <div class="tt4">Ecommerce</div>


    <img class="ship1" src="@/assets/shipping.svg">

    <div class="tt5">Shipping Companies</div>


    <img class="sweet1" src="@/assets/sweet.svg">
    <img class="sweet2" src="@/assets/sweet1.svg">
    <div class="tt6">Bakeries And Sweets</div>



    <img class="public1" src="@/assets/public.svg">
    <img class="public2" src="@/assets/public1.svg">
    <div class="tt7">Publishing Companies</div>


    <img class="trans1" src="@/assets/trans.svg">
    <img class="trans2" src="@/assets/trans2.svg">
    <div class="tt8">Transportation</div>

    <img class="gov" src="@/assets/government.svg">

    <div class="tt9">Government Facilities</div>


    <img class="com1" src="@/assets/com1.svg">
    <img class="com2" src="@/assets/com2.svg">
    <div class="tt10">Commercial Facilities</div>

    <img class="prod1" src="@/assets/prod.svg">
    <img class="prod2" src="@/assets/prod1.svg">
    <div class="tt11">Productive Families</div>

    <img class="mob1" src="@/assets/mob1.svg">
    <img class="mob2" src="@/assets/mob2.svg">
    <div class="tt12">Mobile Application</div>
    </template>
    
    
    
    <style>
  .back{
    background-color: #F5AC01;
    position: absolute;
  height: 91%;
  width: 100%;
  left:0em;
  top:3.4em;
  }
    .top{
      position: absolute;
      left: -60vh;
      top: -13px;
      background: #FAFAFA;
      height:70px;
    width:129.9px;
    opacity:3;
    
    }
    
    .logo{
      position: absolute;
    left:7em;
    background-color:#FFFFFF;
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
  
    .tex1{
      top:5em;
      color: #FAFAFA;
      font-size: 30px;
      font-weight: bold;
      left:2em;
      position: absolute;

    }

    .line-3{
      position: absolute;
      top:12em;
      left:4em;
    }
    

    .rest{
position: absolute;
top:16em;
left:4em;
    }


  .tt1{
    color:#FAFAFA;
    position: absolute;
    top:15em;
    left:7em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .sched{
    position: absolute;
    top:21em;
    left:4em;
  }

  .sched1{
    position: absolute;
    top:21.7em;
    left:4.7em;
  }

  .tt2{
    color:#FAFAFA;
    position: absolute;
    top:19.3em;
    left:7em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .food1{
    position: absolute;
    top:26.7em;
    left:4.6em;
  }

  .food2{
    position: absolute;
    top:26em;
    left:4em;
  }

  .tt3{
    color:#FAFAFA;
    position: absolute;
    top:23.8em;
    left:7em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .eco1{
    position: absolute;
    top:32em;
    left:4.8em;
  }

  .eco2{
    position: absolute;
    top:31em;
    left:4em;
  }

  .tt4{
    color:#FAFAFA;
    position: absolute;
    top:28.3em;
    left:7em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }



  .ship1{
position: absolute;
top:16em;
left:22em;
    }


  .tt5{
    color:#FAFAFA;
    position: absolute;
    top:14.8em;
    left:23em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }



  .sweet1{
    position: absolute;
    top:21.5em;
    left:22.7em;
  }

  .sweet2{
    position: absolute;
    top:21em;
    left:22em;
  }

  .tt6{
    color:#FAFAFA;
    position: absolute;
    top:19.3em;
    left:23em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .public1{
    position: absolute;
    top:26em;
    left:22em;
  }

  .public2{
    position: absolute;
    top:27em;
    left:23em;
  }

  .tt7{
    color:#FAFAFA;
    position: absolute;
    top:23.8em;
    left:23em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }



  .trans1{
    position: absolute;
    top:31em;
    left:22em;
  }

  .trans2{
    position: absolute;
    top:31.8em;
    left:22.7em;
  }

  .tt8{
    color:#FAFAFA;
    position: absolute;
    top:28.3em;
    left:23em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }



  .gov{
position: absolute;
top:16em;
left:43em;
    }


  .tt9{
    color:#FAFAFA;
    position: absolute;
    top:14.8em;
    left:42em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .com1{
    position: absolute;
    top:21em;
    left:43em;
  }

  .com2{
    position: absolute;
    top:21.7em;
    left:43.6em;
  }

  .tt10{
    color:#FAFAFA;
    position: absolute;
    top:19.3em;
    left:42em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .prod1{
    position: absolute;
    top:26em;
    left:43em;
  }

  .prod2{
    position: absolute;
    top:26.7em;
    left:43.8em;
  }

  .tt11{
    color:#FAFAFA;
    position: absolute;
    top:23.8em;
    left:42em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }


  .mob1{
    position: absolute;
    top:31em;
    left:43em;
  }

  .mob2{
    position: absolute;
    top:31.8em;
    left:43.7em;
  }

  .tt12{
    color:#FAFAFA;
    position: absolute;
    top:28.3em;
    left:42em;
    font-weight: lighter;
    font-size: 18px;
    font-family: 'Poppins';
  }

    </style>