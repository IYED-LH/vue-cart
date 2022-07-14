<template>

<nav class="navbar navbar-expand navbar-dark bg-secondary ">
  <div class="container nav-small">

   <div class="collapse navbar-collapse" >
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">About</a>
        <a class="nav-link active" href="#">Contact</a>
        <a class="nav-link active" href="#">FAQ</a>
      </div>
    </div>
    
    <div class="navbar-nav  ms-auto">
        <a class="nav-link active" aria-current="page" href="#"><i class="fa-brands fa-facebook"></i></a>
        <a class="nav-link active"  href="#"><i class="fa-brands fa-instagram"></i></a>
        <a class="nav-link active" href="#"><i class="fa-brands fa-twitter"></i></a>     
    </div>
  
  </div>
</nav>

<nav class="navbar navbar-expand sticky-top navbar-dark bg-primary nav-blue">
<div class="container">
<img src = "@/assets/shoplogo.png"  alt="shoplogo"/>

<SearchBox class="d-none d-lg-inline-flex"/>

<div class="navbar-nav ms-auto">
        <a class="nav-link active cart"  href="#"><i class="fa-solid fa-user"></i></a>
        <a class="nav-link active cart" href="#"><i class="fa-solid fa-cart-shopping"><span class="cart-number">10</span></i></a>     
    </div>

</div>  
</nav>

<div class="m-auto bg-primary">
<SearchBox class="d-inline-flex d-lg-none py-2"/>
</div>

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
  font-family: 'poppins', sans-serif;
  height: 10px; 
  font-size: 14px;
  font-weight: 100;
}
.nav-blue{
  font-family: 'poppins', sans-serif;
  }

img {
  max-width: 40%;
  height: auto;
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
  background-color: #D62828;
  top:  8px;
  right: 2px;
  font-family: 'poppins', sans-serif;
  font-size: 14px;
  font-weight: 100;
  text-align: center;
  padding: 3.5px 0 0 0;  
}

</style>