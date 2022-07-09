<template>

<nav class="navbar navbar-expand navbar-dark bg-secondary">
  <div class="container nav-small">

    <span class="navbar-brand mb-0 h1 "><i class="fa-solid fa-headset"></i> +216 29 896 998</span>
  
  
    
    <div class="navbar-nav ms-auto">
        <a class="nav-link active font-standard" aria-current="page" href="#"><i class="fa-brands fa-facebook"></i></a>
        <a class="nav-link active font-standard"  href="#"><i class="fa-brands fa-instagram"></i></a>
        <a class="nav-link active font-standard" href="#"><i class="fa-brands fa-twitter"></i></a>     
</div>
  
  </div>
</nav>


<nav class="navbar navbar-expand navbar-dark bg-primary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">Home</a>
        <a class="nav-link" href="#">Features</a>
        <a class="nav-link" href="#">Pricing</a>
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
      </div>
    </div>
  </div>
</nav>

</template>

<script>
export default {
  name: 'NavBar',
  
  
}

</script>

<style scoped>

.nav-small{
  height: 18px; 
  font-size: 20px;
  font-weight: 300;
  
}




</style>