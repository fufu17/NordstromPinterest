<template>
  <div id="app">
    <img id='nordstrom' src="./nordstrom-logo.png">
        <h3 id='search'>Sign In</h3>
        <h3 id='sign-in'><i class="fa fa-search" aria-hidden="true"></i> Search</h3>
      <br>
      <br>
      <br>
      <h1 id='toppicks'><b><i>Top Picks from Customers</i></b></h1>
      <hr>
      <div>
          <br>
          <h2 id='pants' @click="footwear=false;pants=true;" :class="{active: pants}">Pants</h2>
          <h2 id='shirt' @click="footwear=true;pants=false;" :class="{active: footwear}">Footwear</h2>
          <br>
          <br>
        </div>
      <hr>
      <div id="Footwear" v-if="footwear">
          <div class='container-fluid'>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot1.jpg">
                    <br>
                    <h2><b class="votes">12</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot2.jpg">
                      <br>
                      <h2><b class="votes">10</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot3.jpg">
                      <br>
                      <h2><b class="votes">9</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot4.jpg">
                      <br>
                      <h2><b class="votes">9</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot5.jpg">
                    <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot6.jpg">
                      <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot7.jpg">
                      <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot8.jpg">
                      <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot9.jpg">
                    <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot10.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot11.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot12.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot13.jpg">
                    <br>
                    <h2><b class="votes">6</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot14.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot15.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/footwear/foot16.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
        </div>
    </div>
      
      
      
    <div id="Pants" v-if="pants">
          <div class='container-fluid'>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant1.jpg">
                    <br>
                    <h2><b class="votes">16</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant2.jpg">
                      <br>
                      <h2><b class="votes">9</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant3.jpg">
                      <br>
                      <h2><b class="votes">9</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant4.jpg">
                      <br>
                      <h2><b class="votes">9</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant5.jpg">
                    <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant6.jpg">
                      <br>
                    <h2><b class="votes">8</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant7.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant8.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant9.jpg">
                    <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant10.jpg">
                      <br>
                    <h2><b class="votes">7</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant11.jpg">
                      <br>
                    <h2><b class="votes">6</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant12.jpg">
                      <br>
                    <h2><b class="votes">6</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
              <hr>
              <div class='row'>
                <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant13.jpg">
                    <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant14.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant15.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
                  <div class="col-lg-3">
                    <img class='pic' src="./assets/pants/pant16.jpg">
                      <br>
                    <h2><b class="votes">5</b>  <i class="fa fa-heart" aria-hidden="true"></i></h2>
                </div>
             </div>
        </div>
    </div>
      
      
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
        footwear: true,
        pants: false
    }
  },
    methods: {
        changePants(){
            
        }
    }
}
</script>

<style>
    #app {
      font-family: 'Lato', sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      color: #2c3e50;
      margin-top: 40px;
    }
    h2{
        display: inline;
        cursor: pointer;
    }
    #pants{
        margin-right:70px;
    }
    #shirt{
        margin-left:70px;
    }
    h3{
        display:inline;
        float:right;
        cursor: pointer;
    }
    #sign-in{
        margin-right:50px;
    }
    #search{
        margin-right:100px;
    }
    #nordstrom{
        margin-left:350px;
    }
    #toppicks{
        color:maroon;
        font-size: 35px;
    }
    .pic{
        object-fit: scale-down;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width:330px;
        height:330px;
        cursor:pointer;
    }
    .pic:hover{
        opacity:0.7;
        cursor:pointer;
    }
    .row{
        margin-bottom:70px;
        margin-top:50px;
    }
    .fa-heart{
        color:red;
    }
    .active{
        color:blue;
    }
</style>
