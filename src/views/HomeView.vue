<template>
<header>

  <NavBar/>
  <ProductCard/>

</header>
    
    
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
