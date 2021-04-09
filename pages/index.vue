<template>
 <v-layout class="hidden-sm-and-down fill-height " style="display:flex; flex-direction:column;" fluid ma-0 pa-0  >     
   <header>
     <bavbar/>
   </header>
   
        
        <section id="landing" style="position:relative; top:40px; height:100vh; background:rgba(255,255,255,0); width:100vw;">
            <div class="sideimg">
              <img class="image" src= "..\assets\school-chemistry-lab-equipment-500x500.jpg" alt="">
              <img  class="image" src="..\assets\Medical_supplies_small.jpg" alt="">
              <img class="image" src="..\assets\tech.jpg" alt=""></div>
            <div class="side"></div>
            <div class="container" id="glass">
             
                <h2>Welcome</h2>
                <h3>
              <span class="medilab"> Medilab & Allied Products K Ltd</span><span style="">  is a Kenyan company, which is committed to providing Medical and Research Reagents and Consumables, Water treatment 
              chemicals, Cooling Tower/Boiler/Chiller chemicals and Condition Monitoring reagents/Sensors.</span>
            </h3>
            <a class="containera" href="/products">Our Products</a>
             
             
            </div>
            
        </section>
       <section class="products">
     <div class="container2">
          <div class="card">

          <div class="cotent">
              <h1>01</h1>
              <img height="120px" width="200px" src="..\assets\380-3808023_medical-supplies-medical-supplies-transparent.png" alt="">
              <h3>Medical supplies</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga harum temporibus nisi culpa aspernatur reprehenderit a provident modi ab eius.</p>
              <a href="#">more</a>
          </div>
      </div>
       <div class="card">
          <div class="cotent">
              <h1>02</h1>
              <img height="120px" src="..\assets\158-1584784_how-chemical-cleaning-supplies-can-help-you-boost.png" alt="">
              <h3>Chemical Reagent</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga harum temporibus nisi culpa aspernatur reprehenderit a provident modi ab eius.</p>
              <a href="#">more</a>
          </div>
      </div>
       <div class="card">
          <div class="cotent">
              <h1>03</h1>
              <img height="120px" src="..\assets\Important-Processes-for-Food-Processing-and-Packaging.jpg" alt="">
              <h3>Processing factory</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga harum temporibus nisi culpa aspernatur reprehenderit a provident modi ab eius.</p>
              <a href="#">more</a>
          </div>
      </div>
   
     </div>
  </section>
        
       
  
   
   

 </v-layout>

</template>
<script>
  const glass =document.getElementById('glass');
  const tl =gsap.timeline({defaults:{ease:"power2.inOut",duration:1.5}})
  tl.from('sideimg',{x:'-10%'})
</script>

<script>
  export default {
    data () {
      return {
        colors: [
          'indigo',
          'warning',
          'pink darken-2',
          'red lighten-1',
          'deep-purple accent-4',
        ],
        slides: [
          'First',
          'Second',
          'Third',
          'Fourth',
          'Fifth',
        ],
      }
    },
  }
</script>

<style  scoped>
#landing{
font-family: noto sans;
padding:14em 14em 14em 20em ;
margin: 0;
}
.sideimg{
  z-index:-1;
  position: absolute;
  height: 100vh;
  width: 100vw;
  top: 0;
  left: 0;
  background: rgba(0, 187, 255, 0.597);
}
.containera{
    position: relative;
    display: inline-block;
    padding: 8px 25px;
    margin-top: 15px;
    background: rgba(0, 0,0, 0.024);
    font-weight: 700;
    font-size: 1.15rem;
    box-shadow: 0 5px 5px rgb(0 0 0 / 43%);
    border-radius: 10px;
    text-decoration: none;
    color: white;

}
.image{
  height: 100vh;
  width: 503px;
  opacity: 0.3;
  z-index: -1000000;
  margin-left: -5px;
}
 .side{
   top: 200px;
   left: 200px;
   position: absolute;
   width: 400px;
   height: 400px;
   background: rgb(8, 195, 220);
   border-radius:50% ;
   display: none;
   z-index: -1;
 }
 .medilab{
   font-size: 3rem;
   font-weight: 900;
   color: white;
 }
 .container{
   display: inline-block;
   background: rgba(243, 243, 243, 0.145);
   width: 40vw;
   padding: 3em;
   border-radius:3em ;
   top: -60px;
   position: relative;
   z-index: 1;
   backdrop-filter: blur(4px);
   border: solid 2px transparent;
   background-clip: padding-box;
   box-shadow: 10px 10px 10px rgba(255, 255, 255,0.3);

 }
 .conatainer h3{
   margin: 0;
   font-size: 2rem;
   color: blue;
   flex-wrap: wrap;
   width: 50vw;
   
 }

h2{
  font-size: 2.6em;
  font-weight: 1000;
}
li{
  float: left;
  line-height: 30px;
  padding: 0px 10px;
  word-wrap: normal;
  list-style-type:none;

}
.main-tag{
  position: relative;
  top: 50%;
  left: 15%;
}
.main-tag h2{
    color: white;
    font-family: noto sans;
    position: relative;
    font-size: 45px;
    top: 50vh;}
/* section 2 */
.products{
    min-height: 130vh;
    margin:0;
    display:flex;

    align-items: center;
    justify-content: center;
    background: rgb(255, 255, 255);

}

.container2{
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: center;
    max-width:100vw;
    flex-wrap: wrap;
    z-index: 10000;
  
    align-items: center;



}
.container2 .card{
    position: relative;
    font-family: noto sans;
    font-size: 14px;
    width: 280px;
    top: 100px;
    height:345px ;
    padding: 19px;
    margin:50px  ;
    margin-bottom: 90px;
    box-shadow: 20px 20px 40px rgba(0, 0, 0, 0.426);
    border-radius: 15px;
    background: rgba(0, 187, 255, 0.145);
     border-top: 1px solid rgba(252, 252, 252, 0.4);
    border-left: 1px solid rgba(252, 252, 252, 0.4);
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(5px);
    
}
.container2 .card .cotent{
    padding: 10px;
    text-align: left;
    transition: 0.5s;
    transform: translateY(10px);
    opacity: 0.5;
}
.container2 .card:hover .cotent{
    
   
    transform: translateY(0px);
    opacity: 1;
}
.container2 .card .cotent p{
   

}
.container2 .card .cotent h1{
    position: absolute;
    top: -10px;
    right: 30px;
    font-size: 3em;
    color: rgba(0, 0, 0, 0.426);
    pointer-events: none;
}
.container2 .card .cotent h1{
    
}
.container2 .card .cotent a{
    position: relative;
    display: inline-block;
    padding: 8px 25px;
    margin-top:15px;
    background: rgba(1, 217, 255, 0.324);
    font-weight: 500;
    box-shadow: 0 5px 5px rgba(0, 0, 0, 0.426);
    border-radius: 10px;
    text-decoration: none;

}
#lastcard{
    margin-bottom:230px;
}
/* end */
@media screen and (max-width: 991px) {
 .image{
  height: 100vh;
  width: 503px;
  display: none;
  opacity: 0.3;
  z-index: -1000000;
  margin-left: -5px;
}
 .container{
   display: inline-block;
   background: rgba(243, 243, 243, 0.145);
   width: 60vw;
   padding: 1em;
   border-radius:3em ;
   top: -170px;
   left:-30vw;
   position: relative;
   z-index: 1;
   backdrop-filter: blur(4px);
   border: solid 2px transparent;
   background-clip: padding-box;
   box-shadow: 10px 10px 10px rgba(255, 255, 255,0.3);

 }
 .conatainer h3{
   margin: 0;
   font-size: 1.5rem;
   color: blue;
   flex-wrap: wrap;
   width: 50vw;
   
 }

h2{
  font-size: 2.6em;
  font-weight: 1000;
}
}
@media screen and (max-width: 600px) {
.image{
  height: 100vh;
  width: 503px;
  opacity: 0.3;
  z-index: -1000000;
  display: none;
  margin-left: -5px;

}
.container{
   display: inline-block;
   background: rgba(243, 243, 243, 0.145);
   width: 85vw;
   padding: 1em;
   border-radius:3em ;
   top: -170px;
   left:-90vw;
   position: relative;
   z-index: 1;
   backdrop-filter: blur(4px);
   border: solid 2px transparent;
   background-clip: padding-box;
   box-shadow: 10px 10px 10px rgba(255, 255, 255,0.3);

 }
 .conatainer h3{
   margin: 0;
   font-size: 1.5rem;
   color: blue;
   flex-wrap: wrap;
   width: 50vw;
   
 }

h2{
  font-size: 2.6em;
  font-weight: 1000;
}
}
</style>