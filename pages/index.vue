<template>
 <v-layout class="hidden-sm-and-down fill-height " fluid ma-0 pa-0 style="" >     
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
                <p>Lorem lit. Cum, exercitationem.</p>
             
            </div>
            <h3>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe delectus suscipit quibusdam amet itaque impedit quod minus ad tempore soluta?
            </h3>
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
 .container{
   display: inline-block;
   background: rgba(243, 243, 243, 0.145);
   width: 350px;
   padding: 3em;
   border-radius:3em ;
   position: relative;
   z-index: 1;
   backdrop-filter: blur(40px);
   border: solid 2px transparent;
   background-clip: padding-box;
   box-shadow: 10px 10px 10px rgba(255, 255, 255,0.3);

 }
 h3,h2,p{
   margin: 0;
   
 }

h2{
  font-size: 2.5em;
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

@media screen and (max-width: 991px) {
 .image{
  height: 100vh;
  width: 503px;
  display: none;
  opacity: 0.3;
  z-index: -1000000;
  margin-left: -5px;
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
}
</style>