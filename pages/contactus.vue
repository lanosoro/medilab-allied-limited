
<template>
  <section class="products">
     <div class="container">
          <div class="card">

          <div class="cotent  col-lg-12 col-lg-2 col-lg-3 col-lg-4 col-lg-5 col-lg-6 col-lg-7 col-lg-8 col-lg-9 col-lg-auto col-md col-md-1 col-md-10 col-md-11 col-md-12 col-md-2 col-md-3 col-md-4 col-md-5 col-md-6 col-md-7 col-md-8 col-md-9">
               <div class="contact-form">
                <span class="circle-one">

                </span>
                <span class="circle-two"></span>
                <form >
                    <h3 class="title-3">Contact us</h3>
                    <div class="input-container">
                        <input type="text" name="name" class="input" placeholder="Username">
                        <label for="">Username</label>
                    </div>
                    <div class="input-container">
                        <input type="email" name="email" class="input" placeholder="Email">
                        <label for="">Email</label>
                    </div>
                    <div class="input-container">
                        <input type="tel" name="phone" class="input" placeholder="phone">
                        <label for="">Phone</label>
                    </div>
                    <div class="input-container textarea">
                        <textarea name="" id="" rows="4" placeholder="message">

                        </textarea>
                        <label for="">message</label>

                    </div>
                    <input type="submit" value="send" class="btn">
                </form>
            </div>
           
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
 .col-lg-12, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-auto, .col-md, .col-md-1, .col-md-10, .col-md-11, .col-md-12, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9 {
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 12px;
    padding-left: 12px;
 }
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
    width: 880px;
    top: 10px;
    height:565px ;
    padding: 19px;
    margin:50px  ;
    margin-bottom: 90px;
    box-shadow: 20px 20px 20px rgba(0, 0, 0, 0.426);
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
    opacity: 1;
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
.contact-container{
  position: relative;
  width: 100%;
  min-height: 100vh;
  padding: 2rem;
  background: #fafafa; 
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}
.form{

  width: 100%;
  max-width: 820px;
  height: 500px;
  background-color: #fff;
  border-radius: 10px;
  z-index: 10000;
  box-shadow: 0 0 20px 1px rgba(0, 16, 242, 0.761);
  grid-template-columns: repeat(2, 1fr);
  display: grid;
}
.contact-form{
  background-color:transparent;
  position: relative;
  border-top-right-radius:10px ;
  border-bottom-right-radius: 10px;
}
.circle-one{
  width: 100px;
  height: 100px;
  border-radius:50% ;
  position: absolute;

}
form{
  padding: 2.3rem 2.2rem;
  z-index: 10;
  overflow: hidden;
  position: relative;

}
.title-3{
  color: white;
  font-weight: 500;
  font-size: 1.5rem;
  line-height: 1;
  margin-bottom: 0.7rem;
}
label{
  display: none;
}
input{
  width: 100%;
  margin-bottom: 30px;
  outline: none;
  border: 2px solid #fafafa;
  background: none;
  padding: 0.6rem 1.2rem;
  position: relative;
  left: -10px;
  color: #fff;
  font-weight: 500;
  font-size: 0.95rem;
  letter-spacing: 0.5px;
  border-radius: 25px;
  transition: 0.3s;
  z-index: 1000000;
}


textarea.input{
    padding: 0.8rem 1.2rem;
  min-height: 150px;
  border-radius: 22px;
  resize: none;
  overflow-y: auto;
  border: none;
  outline: 1px solid white;
  background: #fafafa;
}
.btn {
  padding: 0.6rem 1.3rem;
  background-color: #fff;
  border: 2px solid #fafafa;
  font-size: 0.95rem;
  color: #1abc9c;
  line-height: 1;
  border-radius: 25px;
  outline: none;
  cursor: pointer;
  transition: 0.3s;
  margin: 0;
}

.btn:hover {
  background-color: transparent;
  color: #fff;
}
/* .input-container label {
  position: absolute;
  top: 50%;
  left: 15px;
 
  padding: 0 0.4rem;
  color: #fafafa;
  font-size: 0.9rem;
  font-weight: 400;
  pointer-events: none;
  z-index: 1000;
  transition: 0.5s;
} */

.input-container.textarea label {

}
.input-container span {
  position: absolute;
  top: 0;
  left: 25px;
  transform: translateY(-50%);
  font-size: 0.8rem;
  padding: 0 0.4rem;
  color: transparent;
  pointer-events: none;
  z-index: 500;
}

.input-container span:before,
.input-container span:after {
  content: "";
  position: absolute;
  width: 10%;
  opacity: 1;
  transition: 0.3s;
  height: 5px;
  background-color: #1abc9c;
  top: 50%;
  transform: translateY(-50%);
}

.input-container span:before {
  left: 50%;
}

.input-container span:after {
  right: 50%;
}

@media (max-width:500px){
    .cotent{
        width: 100%;
        padding: 30px;
    }
    .container .card{
    position: relative;
    font-family: noto sans;
    font-size: 14px;
    width: 100%;
    top: 100px;
    height:565px ;
    padding: 19px;
    margin:50px  ;
    margin-bottom: 90px;
    box-shadow: 20px 20px 20px rgba(0, 0, 0, 0.426);
    border-radius: 15px;
    background: rgba(0, 187, 255, 0.166);
     border-top: 1px solid rgba(252, 252, 252, 0.4);
    border-left: 1px solid rgba(252, 252, 252, 0.4);
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(5px);
    
}
}
</style>