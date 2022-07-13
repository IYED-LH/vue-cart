<template>
<header>

  <NavBar/>
</header>

<main>
<div class="container mt-4">
<div class="row g-4">
  <ProductCard />
  <ProductCard />
  <ProductCard />
  <ProductCard />
  <ProductCard />
  <ProductCard />
  <ProductCard />
  <ProductCard />

</div>
</div>
</main>


    
    
</template>

<script>
import NavBar from '../components/NavBar.vue'
import ProductCard from '../components/ProductCard'


export default {
  name: 'HomeView',
  components: {
    NavBar,
    ProductCard
  }
  
    
}
</script>
