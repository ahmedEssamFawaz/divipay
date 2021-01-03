<template>
  <!-- <nav class="navbar navbar-expand-lg navbar-light bg-faded fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse " id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
    </div>
  </div>
</nav> -->
  <nav class="navbar navbar-expand-lg navbar-light text-capitalize">
            <div class="container">
                <a class="navbar-brand" href="#"><img src="imgs/logo.png" alt="#" /></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#show-menu" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="show-menu">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="#home">Home <span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#about">about</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#service">Service</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#agency">travel agency</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">contact us</a>
                        </li>
                       
                    </ul>
                </div>
            </div>
        </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style>

nav.navbar {
    position: absolute;
    top: 0;
    left: 0;
    background-color: transparent;
    width: 100%;
    z-index: 1000;
    font-family: 'Open Sans', sans-serif;
}

nav.navbar a, nav.navbar ul li a {
    color: #FFF !important;
}

nav.navbar ul li {
    padding: 0 15px;
}

nav.navbar .search-container {
    position: relative;
}

nav.navbar form {
    padding: 5px;
    background-color: white;
    position: absolute;
    width: 260px;
    display: none;
}

nav.navbar form input {
    padding: 5px 10px;
    border: 1px solid #b7b5b5;
    background-color: #e6e3e3;
    width: 100%;
}
li {
    list-style-type: none;
}

</style>