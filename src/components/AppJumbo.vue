<template>
    <div>
        <section class="bg">
        <div class="title text-center py-5">
            <h1 class="display-4 fw-bold">Learn At Your Own Pace!</h1>
            <p>Get teamed up with people with the same will</p>
            <div class="right-bar">
                <i class="fa-solid fa-chart-gantt fs-5 py-2"></i> 
                <i class="fa-regular fa-life-ring fs-5  py-2"></i>
                <i class="fa-solid fa-calendar-week fs-5  py-2"></i>
                <i class="fa-solid fa-cart-shopping fs-5  py-2"></i>
            </div>
            <button type="button" class="btn btn-success s-change p-3 btn">Get started for free</button>
        </div>
        <div class="container images">
            <div class="row ">
                <div class="col-3">
                    <img :src="'../img/home-6-hero-left-person-244x300.png'" alt="left-person" class="w-100">
                </div>
                <div class="col-6">
                    <img :src="'../img/home-6-hero-poster-final.jpg'" alt="hero-poster" class="w-100 img-thumbnail">
                    <img :src="'../img/icon-youtube-play.png'" alt="youtube-play" class="yout">
                </div>
                <div class="col-3">
                    <img :src="'../img/home-6-hero-right-person.png'" alt="right-person" class="mt-5 pt-4">
                </div>
            </div>
        </div>
    </section> 
    <!-- fine jumbo header -->

    <!-- citazione -->
        <section class="second py-5 my-5 text-center">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-6">
                        <p class="txt mt-5 pt-5 fs-3">Let passion and determination be the guide along the way and develop at your own pace that's confortable. </p>
                        <h6 fw-bold>FANNIE MORENO</h6>
                        <p class="found">/founder & CEO</p>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script>
export default {
    name:'AppJumbo',
}
</script>
<style lang="scss" scoped>
@import "../styles/vars.scss";


.right-bar{
    position: fixed;
    top: 150px;
    right: 0px;
    width:30px;
    display: flex;
    flex-direction: column;
    border:1px solid black;
    background-color: white;
    color: black;
    
}
.btn{
    background-color: $color-c;
}

.bg{
    background-color:$color-a;
    height: 500px;
    color: white ;
}
.images{
    height: 350px;
    position: relative;
}

.yout{
    position: absolute;
    top: 50%;
    left: 50%;
    transform:translate(-50%, -50%)
}
.txt{
    font-weight: bolder;
    
}
.found{
    font-size: 10px;
    color:$color-b;
}
.s-change:hover{
    background-color: $color-i;
    color:white;
    border-color:$color-i ;
}

</style>