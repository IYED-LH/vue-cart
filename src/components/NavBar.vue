<template>

<nav class="navbar navbar-expand navbar-dark bg-secondary">
  <div class="container nav-small">

   <div class="collapse navbar-collapse" >
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">FAQ</a>
        <a class="nav-link active" href="#">About</a>
        <a class="nav-link active" href="#">Contact</a>
      </div>
    </div>
    
    <div class="navbar-nav ms-auto">
        <a class="nav-link active" aria-current="page" href="#"><i class="fa-brands fa-facebook"></i></a>
        <a class="nav-link active"  href="#"><i class="fa-brands fa-instagram"></i></a>
        <a class="nav-link active" href="#"><i class="fa-brands fa-twitter"></i></a>     
    </div>
  
  </div>
</nav>

<nav class="navbar navbar-expand navbar-dark bg-primary">
<div class="container">
<img src = "@/assets/shoplogo.png" alt="shoplogo"/>
<SearchBox/>

<div class="navbar-nav ms-auto">
        <a class="nav-link active cart"  href="#"><i class="fa-solid fa-user"></i></a>
        <a class="nav-link active cart" href="#"><i class="fa-solid fa-cart-shopping"><span class="cart-number">2</span></i></a>     
    </div>


</div>  
</nav>

</template>

<script>
import SearchBox from './/SearchBox.vue'
export default {
  name: 'NavBar',
  components: {
    SearchBox
  }
  
  
}

</script>

<style scoped>

.nav-small{
  font-family: 'montserrat', sans-serif;
  height: 10px; 
  font-size: 14px;
  font-weight: 100;
  
}

img{
  height: 15%;
  width: 15%;
}

.cart{
  font-size: 30px;
  position: relative; 
  margin-right: 10px;

}

.cart-number{
  position: absolute;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  background-color: red;
  top:  8px;
  right: 2px;
  font-size: 12px;
  text-align: center;
  padding: 3px 0 0 0;


  
  


 
  
  
  
}










</style>