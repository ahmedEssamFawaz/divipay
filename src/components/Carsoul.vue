<template>
<!-- <div class="">
    <div class="holder">
<img src="/img/PBLTHH0.jpg" alt="" class="img-fluid">
    <div class="words">
         <h1 class="title">Divipay System</h1>
         </div>
         <div class="p">
              <pre>Lorem ipsum ias id! Debitis voluptatibus, 
            deleniti natus consequatur placeat dignissimos 
            fugit, 
                  velit sapiente facere soluta aliquid nemo iure.</pre>
         </div>
   
    <button>Request Demo</button>
    <button>Apple</button>
    <button>Windows</button>


    </div>

    
    
   
</div>
   -->
    <header id="home">
            <div class="overlay">
                <div class="container">
                    <div>
                        <h1><span>Amazing</span><br>Santorini 10 Days Tour</h1>
                        <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as</p>
                        <button><a href="#" class="text-uppercase">book now</a></button>
                    </div>
                </div>
            </div>
            
        </header>
        
</template>

<script>
export default {
  name: 'Carsoul'
}
</script>

<style scoped>
header {
    background-image: url(/img/PBLTHH0.jpg);
    background-size: cover;
    height: 1000px;
}

.overlay {
    background-color: rgba(0, 0, 0, .51);
    width: 100%;
    height: 100%;
}

header {
    position: relative;
    color: #FFF;
    font-family: 'Roboto', sans-serif;
}

header .container {
    height: 100%
}

header .container > div {
    margin: 0 auto;
    position: relative;
    top: 320px;
    right: 0px;
/*    text-align: center;*/
}

header .container > div h1 {
    font-size: 90px;
}

header button {
    background-color: transparent;
    display: block;
    border: 1px solid #FFF;
    border-radius: 50px;
    padding: 0;
    margin: 30px auto;
}

header button a {
    padding: 10px 40px;
    display: block;
    color: #FFF;
}

header button:hover {
    background-color: #bd8cbf;
    border: 1px solid #bd8cbf;
}

header button:hover a {
    color: white;
}

</style>