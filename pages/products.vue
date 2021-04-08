
<template>
  <section class="products">
     <div class="container">
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
       <div class="card">
          <div class="cotent">
              <h1>04</h1>
              <h3>powerplant </h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga harum temporibus nisi culpa aspernatur reprehenderit a provident modi ab eius.</p>
              <a href="#">more</a>
          </div>
      </div>
       <div class="card" id="lastcard">
          <div class="cotent">
              <h1>05</h1>
              <img height="120px" src="..\assets\index.jpg" alt="">
              <h3>water treatment reagents</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga harum temporibus nisi culpa aspernatur reprehenderit a provident modi ab eius.</p>
              <a href="#">more</a>
          </div>
      </div>
     </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.products{
    min-height: 130vh;
    margin:0;
    display:flex;
    align-items: center;
    justify-content: center;
    background: rgb(255, 255, 255);

}
.products::before{
    content: '';
    position: absolute;
    top: 40vh;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0, 187, 255, 0.597),white );
    clip-path: circle(30% at right 50%);
}
.products::after{
    content: '';
    position: absolute;
    top: 40px;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0, 187, 255, 0.597),white );
    clip-path: circle(20% at 10% 40%);
}
.products::after{
    content: '';
    position: absolute;
    top: 80px;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0, 187, 255, 0.597),white );
    clip-path: circle(20% at 10% 40%);
}
.container{
    position: relative;
    display: flex;
    justify-content: center;
    max-width:1200px;
    flex-wrap: wrap;
    z-index: 10000;
    overflow: hidden;



}
.container .card{
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
    background: rgba(0, 187, 255, 0.166);
     border-top: 1px solid rgba(252, 252, 252, 0.4);
    border-left: 1px solid rgba(252, 252, 252, 0.4);
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(5px);
    
}
.container .card .cotent{
    padding: 10px;
    text-align: left;
    transition: 0.5s;
    transform: translateY(10px);
    opacity: 0.5;
}
.container .card:hover .cotent{
    
   
    transform: translateY(0px);
    opacity: 1;
}
.container .card .cotent p{
   

}
.container .card .cotent h1{
    position: absolute;
    top: -10px;
    right: 30px;
    font-size: 3em;
    color: rgba(0, 0, 0, 0.426);
    pointer-events: none;
}
.container .card .cotent h1{
    
}
.container .card .cotent a{
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
</style>