<template>
<div class="input-group">
 <form class="d-flex mx-5 my-auto d-inline w-100">
        <input class="form-control search-box" type="search" placeholder="What are you looking for?" aria-label="Search">
        <button class="btn btn-secondary px-4"><i class="fa-solid fa-magnifying-glass"></i></button>
     </form>
      </div>

</template>


<script>

export default {
  name: 'SearchBox',
  
}

</script>


<style scoped>

.btn-secondary{
 border-radius: 0 25px 25px 0;
 
}

.search-box{
border-radius: 5px 0 0 5px;
transition: 0.6s ease-in-out;
}


.search-box:focus{
border-radius: 25px 0 0 25px;

}

</style>

