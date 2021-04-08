<template>
  <header>
      <nav>
         <a class="logo" href="#"><img class="img" src="..\assets\logo-medilab-removebg-preview.png" alt=""></a>
         <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/products">Products</a></li>
            <li><a href="#">contact us </a></li>
            <li><a href="/about">about us </a></li>
   
            
             </ul> 
      </nav>
       <div class="hamburger-menu-container">
      <div class="hamburger-menu">
        <div></div>
      </div></div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
header{
    position: fixed;
    top: 0px;
    left: 0px;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: 0.7s;
    padding: 40px 100px;
    height: 40px;
    z-index: auto;
    font-family: noto sans;
    z-index: 100000;
    background: rgb(255, 255, 255);
    box-shadow: 0 5px 5px rgba(158, 158, 158, 0.4);
}
header nav{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    
}
.img
{
 
    
}
header nav .logo{
    text-decoration: none;
    font-size: 2em;
    font-weight: 700;
    color: #fff;
    transition: 0.7s;
    text-transform: uppercase;


}
header nav ul li{
    list-style: none;
    position: relative;
  
}
header nav ul li a{
    text-decoration: none;
    list-style: none;
    color: rgb(0, 238, 255);
    font-size: 16px;
    font-weight: 400;
    margin: 0 15px;
    position: relative;
    transition: 0.6s;
    text-decoration: none;
}
header nav ul li a:hover, a::before{
  color: #00aeff;
  border-bottom-color: #00aeff;
  transition: width 2.4s linear;
  transition-property: border-bottom; 
}

header ul{
    display: flex;
    position: relative;
    align-items: center;
    justify-content: center;

}
.hamburger-menu-container {
  flex: 1;

  display: none;
  align-items: center;
  justify-content: flex-end;
}

.hamburger-menu {
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  align-items: center;

  justify-content: flex-end;
  margin-top: -90px;
}

.hamburger-menu div {
  width: 1.6rem;
  height: 3px;
  border-radius: 3px;
  background-color: #69bde7;
  position: relative;
  z-index: 1001;
  transition: 0.5s;
}

.hamburger-menu div:before,
.hamburger-menu div:after {
  content: "";
  position: absolute;
  width: inherit;
  height: inherit;
  background-color: black;
  z-index: 20000;
  border-radius: 3px;
  transition: 0.5s;
}

.hamburger-menu div:before {
  transform: translateY(-7px);
}

.hamburger-menu div:after {
  transform: translateY(7px);
  color: white;
}
@media  (max-width:761px) {
    
header ul{
    display: none;
    position: relative;
    align-items: center;
    justify-content: center;

}
.logo{
    position: relative;
    left: -100px;
    
}
.img{
    height: 60px;
}
}
@media (max-width:991) {
    .image{
        display: none;
    }
}

</style>