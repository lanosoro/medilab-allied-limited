<template>
  <main>
    <bavbar/>
    <nuxt/>
     <footer style="bottom:0; position:relative; width:100%; " class="justify-center">
      
        <div class="container">
      <div class="sec aboutus">
        <h3>
          About Us
        </h3>
        <p style="padding-top:30px">
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
          
        </p>
        <ul class="sci">
          <li>
            <a href="#"><i class="fab fa-facebook-f"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-twitter"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-instagram"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-linkedin-in"></i></a>
          </li>
        </ul>
      </div>
      <div class="sec links">
        <h3>
          Other Links
        </h3>
        <ul>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact Us</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Terms & conditions</a></li>
        </ul>
      </div>
      <div class="sec contact">
        <h3>Contact Info</h3>
        <ul class="info">
          <li>
            <span style="font-size:13px"><i></i>MEDILAB AND ALLIED PRODUCTS (K) LTD,</span>
          </li>
          <li>
            <span
              ><i class="fa fa-map-marker" aria-hidden="true"></i> GENERAL
              WARUINGE ROAD, OLD RACE COURSE, STAREHE COURT 7638 (2), P.O BOX
              14705-00400, NAIROBI, KENYA</span
            >
          </li>
          <li>
            <span
              ><i class="fa fa-phone"></i> +254 721 811 499, +254 734 768 110,
              +254 020 4401525, +254 774 768 110</span
            >
          </li>
          <li>
            <span style="line-height:1.5em;"
              ><i class="fa fa-envelope"></i> sales@medilaballied.com
              info@medilaballied.com medilab.alliedproductsltd@gmail.com</span
            >
          </li>
        </ul>
      </div>
    </div>
    <div id="bottomfooter">
     <p style="font-size:12px;"> Copyright © {{ new Date().getFullYear() }}· All Rights Reserved · Medilabs
      Ltd Web design by ·<span id="link">
        <a href="http://fineteklabs.com"> Fineteklabs</a>
      </span></p>
    </div>
  
  
  </footer>
  </main>
</template>

<script>
import bavbar from '../components/bavbar.vue'
export default {
  components: { bavbar },

}
</script>

<style>

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
    top: 50vh;
}
li a{
 
  color: #737373;
  text-decoration: none; /* no underline */
  margin-right: 0%;
 
}
ul{
  list-style-type:none;
  font-size: 12px;
  
}
ul.b{
  line-height: 200%;
  text-align: justify;
}
a{
  text-decoration: none;
}
a:hover{
  text-decoration: underline;
}
footer {
  display: flex;
  justify-content: space-between;
  font-family: sans-serif;
  min-height: 50vh;
  flex-direction: column;
  background: #0074a5;
  padding: 40px;
  width: 100%;
  position: relative;
  flex-wrap: wrap;
}
footer .container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  margin: 20px 20px;
  flex-direction: row;
  max-width: 100%;
  top: -18px;
  left: -18px;
  position: relative;
}
footer .container .sec {
  margin-right: 0px;
  font-size: 14px;
}
footer .container .sec.aboutus {
  width: 40%;
  color: white;
  word-spacing: 0.2em;
}
.sci {
  margin-top: 20px;
  display: flex;
}
.sci li {
  list-style: none;
}
.sec.aboutus h3::before {
  content: "";
  position: absolute;

  background: white;
  height: 2px;
  margin-top: 20px;
  box-sizing: border-box;
  width: 100px;
}
.sci li a {
  display: inline-block;
  width: 40px;

  height: 40px;
  background-color: rgba(255, 255, 255, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  color: white;
  text-decoration: none;
  margin-right: 30px;
  transition: all 1s ease;
}
.sci li a:hover {
  background: white;
  color: #0074a5;
}
.links li a {
  display: inline-block;
  display: flex;
  justify-content: center;
  align-items: center;

  color: white;
  text-decoration: none;
  margin-right: 35px;
  transition: all 1s ease;
}
.links li {
  list-style: none;
}
footer .container .links {
    width: 170px;
    position: relative;
    color: white;
    display: block;
}
.links ul li {
  text-decoration: none;
  margin-top: 10px;
  margin-bottom: 10px;
  justify-content: flex-start;
  display: flex;
  text-align: left;
  align-self: auto;
  align-items: left;
  flex-wrap: wrap;
  transition: all 0.1s ease-in;
  word-spacing: 0.2em;
}
.links ul li:hover {
 
  font-size: 19px;
}
.links h3::before {
  content: "";
  position: absolute;
  background: white;
  height: 2px;
  margin-top: 20px;
  box-sizing: border-box;
  width: 100px;
}
.contact {
  width: calc(35% - 70px);
  margin-right: 0 !important;
  color: white;
  list-style: none;
}
.contact .info {
  position: relative;
}
.contact .info li {
  display: flex;
  margin-bottom: 16px;
  word-spacing: 0.1em;
  padding-top: 6px;
}
.contact h3::before {
  content: "";
  position: absolute;
  background: white;
  height: 2px;
  margin-top: 20px;
  box-sizing: border-box;
  width: 100px;
}
#bottomfooter {
  position: absolute;
  left: auto;
  right: 0;
  font-size: 12px;
  margin-top: 300px;
  bottom: 0px;
  background: #28b6e7;
  width: 100%;
  padding: 30px;
  color: white;
  font-weight: 400;
  font-size: 18px;
  justify-content: center;
  text-align: center;
}
@media screen and (max-width: 991px) {
  footer {
    padding: 20px;
    font-family: noto sans;
  }
  footer .container {
    flex-direction: column;
    justify-content: center;
    position: relative;
    left: -10px;
  }
  .container .sec {
    margin-right: 0;
    margin-bottom: 40px;
  }
  #bottomfooter {
    position: absolute;
    left: auto;
    right: 0;
    bottom: 0px;
    background: #28b6e7;
    width: 100vw;
    padding: 8px 40px;
    color: white;
    font-weight: 400;
    font-size: 18px;
    justify-content: center;
    text-align: center;
    margin-top: 20px;
  }
  h3 {
    margin-bottom: 0.5rem;
    font-family: inherit;
    font-weight: 500;
    line-height: 1.2;
    width: 300px;
    color: inherit;
  }
  .contact .info {
    position: relative;
    width: 50vw;
  }
  footer .container .sec.aboutus p{
  width: 500px;
}
footer .container .links {
    width: 170px;
    position: relative;
    color: white;
    display: block;
}
}
@media screen and (max-width: 600px) {

footer .container .sec.aboutus p{
  width: 300px;
}
footer .container .links {
    width: 170px;
    position: relative;
    color: white;
    display: block;
}
.sci li {
  list-style: none;
  position: relative;
  left: -8.7;
}
.sci li a {
  display: inline-block;
  width: 40px;

  height: 40px;
  background-color: rgba(255, 255, 255, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  color: white;
  text-decoration: none;
 
  transition: all 1s ease;
}
footer .container .sec.aboutus p {
    width: 200px;
    flex-wrap: wrap;
}
}
</style>