<template>

   <div class="hello">
    <nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#"><img :src="'../img/light-logo.png'" alt="logo " class="logo mt-2"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item dropdown ">
          <a class=" dropdown-toggle white" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Home
          </a>
        
        <li class="nav-item dropdown "  >
          <a class=" dropdown-toggle white" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Pages
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Start Here</a></li>
            <li><a class="dropdown-item" href="#">Success Story</a></li>
            <li><a class="dropdown-item"  href="#">About me</a></li>
            <li><a class="dropdown-item" href="#">Contact me</a></li>
            <li><a class="dropdown-item" href="#">Contact us</a></li>
            <li><a class="dropdown-item" href="#">Purchase guide</a></li>
            <li><a class="dropdown-item" href="#">Privacy Policy</a></li>
            <li><a class="dropdown-item" href="#">Term of Service</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="white dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Courses
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown" >
            <li><a class="dropdown-item" href="#">Courses Grid</a></li>
            <li><a class="dropdown-item" href="#">Membership Levels</a></li>
            <li><a class="dropdown-item" href="#">Become a Teacher </a></li>
            <li><a class="dropdown-item" href="#">Profile</a></li>
            <li><a class="dropdown-item" href="#">Checkout</a></li>
            <li><a class="dropdown-item" href="#">Single Layout</a></li>

          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="white dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Features
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown" >
            <li><a class="dropdown-item" href="#">Event</a></li>
            <li><a class="dropdown-item" href="#">Zoom Meeting</a></li>
            
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="white dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="true" >
            Blog
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown" >
            <li><a class="dropdown-item" href="#">Blog Grid</a></li>
            <li><a class="dropdown-item" href="#">Blog Masonry</a></li>
            <li><a class="dropdown-item" href="#">Blog Classic</a></li>
            <li><a class="dropdown-item" href="#">Blog List</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="white dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Shop
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown" >
            <li><a class="dropdown-item" href="#">Cart</a></li>
            <li><a class="dropdown-item" href="#">Whishlist</a></li>
            <li><a class="dropdown-item" href="#">Single Product</a></li>
          </ul>
        </li>
        <li>
          <i class="fa-solid fa-cart-shopping fs-4"></i>
        </li>
      </ul>
      <form class="d-flex">
        <i class="fa-regular fa-user fs-5 my-user"></i>
      <input type="text" class="form-control mt-2" placeholder="Search.." aria-label="Recipient's username" aria-describedby="button-addon2">
              <button class="btn btn-light mt-2 " type="button" id="button-addon2"><i class="fa-solid fa-magnifying-glass glass"></i></button>
      </form>
    </div>
  </div>
</nav>
</div>
</template>

<script>

export default {
  name: 'AppHeader',

}

</script>


<style  lang="scss" scoped>
@import "../styles/vars.scss";



nav{
  background-color: $color-a;
}
.white{
  color:white;
  text-decoration:none;
}

.logo{
  height: 50px;
}
.hello{
  background-color: $color-a;
}
.glass{
  color: $color-c;
}
ul{
  list-style-type: none;

}

li{

  padding: 20px;
  position: relative;


}
li:hover {
  color: white;

}
 li:hover .dropdown-menu{
   transition: 0.8s ease;
   display: block;
   margin-top:15px;
   padding:10px;
 }

li::before {
  content: "";
  position: absolute;
  display: block;
  width: 100%;
  height: 2px;
  top: 10px;
  left: 0;
  background-color: white;
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

li:hover::before {
  transform: scaleX(1);
}

i{
  font-size: 10px;
  padding: 5px;
}
a{
 
  text-decoration: none;
}
.my-user{
  width: 30px;
  height: 30px;
  margin-top: 10px;
  margin-right: 22px;
  line-height: 15px;
  color: white;
}
.fa-solid.fa-cart-shopping{
  color: white;
}


</style>
