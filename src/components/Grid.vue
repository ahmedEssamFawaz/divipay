<template>
<div class="container">
  <div class="card" style="width: 18rem;">
  <i class="fas fa-headphones-alt fa-8x"></i>
  <div class="card-body">
    <h5 class="card-title">Works offline</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    
  </div>
</div>
 <div class="card" style="width: 18rem;">
 <i class="fas fa-sms fa-8x"></i>
  <div class="card-body">
    <h5 class="card-title">Manage remotely</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    
  </div>
</div>
 <div class="card" style="width: 18rem;">
  <i class="fas fa-cogs fa-8x"></i>
  <div class="card-body">
    <h5 class="card-title">Real time Reports</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    
  </div>
</div>
</div>
</template>

<script>
export default {
 name: "Grid"
}
</script>

<style scoped>
.container{
    position: absolute;
    display: flex;
    justify-content: space-around;
    left: 20%;
    top:100%;
   
}
i {
    padding-top: 19px;
}

h5{
    font-weight: bolder;
    font-size: 25px;
    padding-bottom: 10px;
}

.card-text{
    font-weight: 500;
    
}
</style>