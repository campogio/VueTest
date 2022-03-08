<template>

<section>

        <!-- INIZIO HEADER -->
        <header>
            <div class="container-lg">
                <nav>
                
                    <!-- Box-logo -->
                    <div class="box-logo">
                        <img src="./construction_logo.png" alt="construction_mobile">
                    </div>
                   
    
                    <!-- BOX LINK -->
                    <div class="box-link">
                        <ul>
                             <li v-for="item in items" :key="item.title">
                            {{ item.title }}
                            </li>
                        </ul>
                        <a class="btn btn-nav" href="#">get quote</a>
                    </div>
                    

                </nav>
            </div>

            <!-- JUMBOTRON -->
            <div class="jumbotron ">
                    <div class="box-item-jumbo">
                        <h1>building inspiring spaces</h1>
                        <p>we build inspiring residential & commercial spaces</p>
                        <div class="box-btn-jumbo">
                            <a class="btn-grey" href="#">explore recent work</a>
                            <a class="btn" href="#">get a quote today</a>
                        </div>
                    </div>
            </div>
           
        </header>
        

</section>
  
</template>




<script>
export default {
    name: 'MyHeader',



data(){
    return{
        counter: 0,
         items: [
        {
          title: "home",
        },
        {
          title: "about ",
        },
        {
          title: "service",
        },
        {
          title: "work",
        },
        {
          title: "articles",
        },
      ],
        
    };
  },

  methods: {
       

  },
};
</script>




<style lang="scss">

/* HEADER */
header{
    width: 100%;
}
header nav{
    display: flex;
    width: 100%;
    height: 100px;
    align-items: center;
    padding: 20px 0;
}
header nav .box-logo{
    flex-basis: 30%;
}
header nav .box-logo img{
    width: 45%;
}
header nav .box-link{
    flex-grow: 1;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
header nav .box-link ul{
    display: flex;
    list-style: none;
}
header nav .box-link ul li{
    padding:0 22px;
    font-size: 12px;
    position: relative;
}
header nav .box-link ul li.active a{
    color:#fed23f;
}
header nav .box-link ul li::after{
    content: "\f0dd";
    font-weight: 900;
    font-family: "Font Awesome 5 Free";
    font-size: 38px;
    color: #fff;
    position: absolute;
    top: 31px;
    left: 50%;
    opacity: 0;
    transform: translateX(-50%);
    transition: all 0.5s;
    z-index: 100;
}
header nav .box-link ul li:hover::after,
header nav .box-link ul li.active::after {
    opacity: 1;
}
header nav .box-link .btn-nav{
    padding: 8px 20px;
}

header nav .box-link .btn-nav:hover{
    background-color: #000;
    color: #fff;
}
.jumbotron{
    background-image: url('home-slider-62528242.jpg');
    height: 610px;
    background-position: 0px 25%;
    background-repeat: no-repeat;
    background-size: cover;
    text-align: center;
    position: relative;
}

.jumbotron .box-item-jumbo{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50% ,-50%);
}

.jumbotron p{
    text-transform: capitalize;
    color:#fed23f;
    margin: 20px 0;
    font-size: 1.2em;
    opacity: 0.8;
}

.jumbotron .box-btn-jumbo{
    margin-top: 35px;
    flex-wrap: wrap;
    display: flex;
    justify-content: center;
}

.jumbotron .box-btn-jumbo a{
    margin: 10px 8px;
    padding: 11px 40px;
    font-size: 0.9em;
}

.jumbotron .box-btn-jumbo a.btn-grey{
    color:#fff;
    background-color: #333333;
}

.jumbotron .box-btn-jumbo a.btn:hover{
    background-color: #000;
    color: #f5f5f5;
}

.jumbotron .box-btn-jumbo a.btn-grey:hover{
    background-color: #f9d03f;
    color: #31312f;
}



</style>