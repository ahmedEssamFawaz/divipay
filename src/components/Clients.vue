<template>
 
<div class="container-fluid">
     <h1 class="text-center py-5">
 our clients
</h1>
  <section class="scrolling-carousel py-5">
    <div class="d-flex">
      <div class="d-flex flex-row category px-2" id="category">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Others/documentation/3.jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Others/documentation/4.jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Photos/Lightbox/Thumbnail/img%20(147).jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(55)-mini.jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Photos/Lightbox/Thumbnail/img%20(151).jpg" class="px-3"  width="400px" height="200px"/>
        <img src="https://mdbootstrap.com/img/Photos/Lightbox/Thumbnail/img%20(42).jpg" class="px-3"  width="400px" height="200px"/>
      </div>
    </div>
  </section>
</div>

</template>

<script>
export default {
  name: "Clients"
}
</script>

<style scoped>
.container-fluid{
    padding-top: 400px;
}
.category {
  overflow-x: auto;
  -ms-overflow-style: none; /* IE 11 */
  scrollbar-width: none; /* Firefox 64 */
}
.category::-webkit-scrollbar {
  display: none;
}

h1{
    font-weight: bold;
}

</style>