<template>
 <section class="about"> 
 <div class="col-lg-4 col-md-8 col-sm-12 top" id="top"> 
   <span class="about-opener">
  Medilab & Allied 
Products K Ltd is a 
Kenyan company, 
which is committed 
to providing Medical
and Research 
Reagents and 
Consumables, Water 
treatment chemicals, 
Cooling 
Tower/Boiler/Chiller
chemicals and
Condition Monitoring 
reagents/Sensors.
   </span>
 </div>
 </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.about{
  height: 100vh;
  width: 100vw;
  margin: 0;
  background-size: cover;

  font-weight: 600;
  font-size: 18px;
  font-family: noto sans;
  display: block;
  justify-content: center;
  align-content: center;
}
.about-opener[data-v-0a606064] {
    width: 60vw;
    position: relative;
    flex-flow: row wrap;
    position: absolute;
    top: 25vh;
    width: 400px;
    overflow: hidden;}
.top{
  width: 500px;
  height: 80vh;
  position: absolute;
  top:50%;
  background: white;
  box-shadow: 0 3px 3px rgba(0, 208, 255, 0.446);
  left: 50%;
  transform: translate(-50%, 50%);
}

@media (min-width: 600px){
.col-sm-12 {
    flex: 0 0 100%;
    max-width: 80%;
    max-height: 80vh;
    position: absolute;
    top: 100px;
    background: rgba(0, 208, 255, 0.446);
}
footer .container .sec.aboutus p {
    width: 300px;
    flex-wrap: wrap;
}}
</style>