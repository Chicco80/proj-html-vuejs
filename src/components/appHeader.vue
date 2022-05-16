<template>
  <div class="hello">
    <div class="container-fluid">
      <div class="container">
        <div class="row">
          <div class="col-4">
            <!-- <img src="../public/img/artist-blog-01-480x325.jpg" alt=""> -->
          </div>
          <div class="col-4">
            <ul>
              <li v-for="dato in myDati" :key="dato"> <a href="#">{{myDati[0].link}}</a>
                <span><i class="fa-solid fa-chevron-down"></i></span>
              </li>
            </ul>
          </div>
          <div class="col-4">
            <div class="input-group mb-3">
              <input type="text" class="form-control" placeholder="Search.." aria-label="Recipient's username" aria-describedby="button-addon2">
              <button class="btn btn-light " type="button" id="button-addon2"><i class="fa-solid fa-magnifying-glass glass"></i></button>
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


.hello{
  background-color: $color-a;
  color: white;
}
.glass{
  color: $color-c;
}



</style>
