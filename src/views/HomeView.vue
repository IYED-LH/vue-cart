<template>

  <NavBar/>

<div class="container mt-4">
<div class="row g-4">
  <ProductCard :key="product.id" v-for="product in products" :product="product"/>
  
  

</div>
</div>



    
    
</template>

<script>
const axios = require('axios').default;
import NavBar from '../components/NavBar.vue'
import ProductCard from '../components/ProductCard'


export default {
  name: 'HomeView',
  components: {
    NavBar,
    ProductCard
  },

  data(){
    return {
      products: []

  }
  },


  methods: {
    async fetchProducts() {
       try {
         const response = await axios.get('https://fakestoreapi.com/products');
         this.products = response.data;
         
       
       } catch (error) {
         alert('can not fetch products');
       }
       
      
    }
    
  },
 
mounted() {
  this.fetchProducts();
}

    
}
</script>
