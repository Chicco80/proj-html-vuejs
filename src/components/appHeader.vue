<template>
  <div class="hello">
    <div class="container-fluid">
      <!-- <img :src="'../img/jumbotron-background-wave-big.svg'" alt="" class="wave"> -->
      <div class="container">
        <div class="row">
          <div class="col-3">
            <img :src="'../img/light-logo.png'" alt="logo " class="logo mt-2">
          </div>
          <div class="col-6">
            <ul class="d-flex">
              <li v-for="dato in myDati" :key="dato"> <a href="#"></a>{{dato.link}}
                <span><i class="fa-solid fa-chevron-down"></i></span>
              </li>
              <li>
                <i class="fa-solid fa-cart-shopping fs-5 "></i>
              </li>
            </ul>
          </div>
          <div class="col-3">
            <div class="input-group mb-3">
              <i class="fa-regular fa-user fs-5 my-user"></i>
              <input type="text" class="form-control mt-2" placeholder="Search.." aria-label="Recipient's username" aria-describedby="button-addon2">
              <button class="btn btn-light mt-2 " type="button" id="button-addon2"><i class="fa-solid fa-magnifying-glass glass"></i></button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import dati from '../dati.json'

export default {
  name: 'AppHeader',
  data(){
  return{
    myDati: dati
  }
}
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  lang="scss">
@import "../styles/vars.scss";


// .wave{
//   transform: rotate(180deg);
//   width:100%;
// }
.logo{
  height: 50px;
}
.hello{
  background-color: $color-a;
  color: white;

}
.glass{
  color: $color-c;
}
ul{
  list-style-type: none;
  // text-decoration: none;
  
}
li{
  padding: 10px;


}
i{
  font-size: 10px;
  padding: 5px;
}
a{
  color: white;
  text-decoration: none;
}
.my-user{
  // border: 1px solid white;
  width: 30px;
  height: 30px;
  margin-top: 10px;
  margin-right: 22px;
  line-height: 15px;
  // border-radius: 50%;
}



</style>
