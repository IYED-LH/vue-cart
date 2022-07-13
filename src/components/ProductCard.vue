<template>

<div class="col-xl-4 col-md-6 col-12">
<div class="card px-2">

  <img class="card-img-top image-size p-4 pb-0" src="https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg"  alt="product">
  
  <div class="card-body">
    
    <h5 class="card-title">Fjallraven - Foldsack No. 1 Backpack, Fits 15 Laptops</h5>
    
    <p class="card-text text">Your perfect pack for everyday use and walks in the forest. Stash your laptop (up to 15 inches) in the padded sleeve, your everyday </p>

<div class="d-flex justify-content-between align-items-center">   
    
    <h5 class="price-font ps-3" ><span class="dollar-price">$</span>109.95</h5>
    
    <button class="btn btn-secondary add-cart-btn py-2"><i class="fa-solid fa-cart-shopping pe-2"></i>Add to Cart</button>
 
 
  </div>
  </div>
</div>
</div>


</template>

<script>
export default {
  name: 'ProductCard',

}

</script>

<style scoped>
.image-size{
width: 100%;
height: 18rem;
object-fit: contain;
}

.card{
    
    border-radius: 16px;
    transition: 0.5s ease all;
}

.card:hover{
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.095), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    
       
}

h5{
    font-weight: 700;

}

.price-font{
    font-weight: 700;
    font-size: 2rem;
    position: relative;
}

.dollar-price{
    position: absolute;
    font-size: 1rem;
    font-weight: 300;
    right: 100px;
}

.add-cart-btn{
    border-radius: 6px;
}

.text{
   overflow: hidden;
   text-overflow: ellipsis;
   display: -webkit-box;
   -webkit-line-clamp: 2; /* number of lines to show */
   -webkit-box-orient: vertical;
}

.round-btn{
  width: 40px;
  height: 40px;
  border-radius: 50%;
}


</style>


