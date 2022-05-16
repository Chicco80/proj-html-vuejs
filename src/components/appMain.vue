<template>
<div>
    <section class="bg">
        <div class="title text-center py-5">
            <h1>Learn At Your Own Pace!</h1>
            <p>Get teamed up with people with the same will</p>
            <button type="button" class="btn btn-success">Get started for free</button>
        </div>
        <div class="container images">
            <div class="row ">
                <div class="col-3">
                    <img :src="'../img/home-6-hero-left-person.png'" alt="left-person" class="w-100 left">
                </div>
                <div class="col-6">
                    <img :src="'../img/home-6-hero-poster-final.jpg'" alt="hero-poster" class="w-100 center img-thumbnail">
                    <img :src="'../img/icon-youtube-play.png'" alt="youtube-play" class="yout">
                </div> 
                <div class="col-3">
                    <img :src="'../img/home-6-hero-right-person.png'" alt="right-person" class="w-100 h-100 right">
                </div>
            </div>
        </div>
    </section>
        <section class="second py-5 my-5 text-center">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-5">
                        <p class="txt mt-5 pt-5">Let passion and determination be the guide along the way and develop at your own pace that's confortable. </p>
                        <h6>FANNI MORENO</h6>
                        <p class="found">/founder & CEO</p>
                    </div>
                </div>
            </div>
        </section>
        <div class="number">
            <div class="row justify-content-center text-center">
                <div class="col-2">
                   <p class="green">1.926</p> 
                   <p class="small">FINISHED SESSION</p>
                </div>
                <div class="col-2">
                    <p class="green">3.092+</p>
                    <p class="small">ENROLLED LEANERS</p>
                </div>
                <div class="col-2">
                    <p class="green">200</p>
                    <p class="small">ONLINE INSTRUCTION</p>
                </div>
                <div class="col-2">
                    <p class="green">100%</p>
                    <p class="small">SATISFACTION RATE</p>
                </div>

            </div>
        </div>
        
</div>
</template>

<script>
export default {
    name: 'AppMain',
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";

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
.second{
    //  background-image: url("../img/maxcoach-shape-05.png");
    color:black;
    display: flex;
}
.txt{
    font-weight: bolder;
    font-size: 18px;
}
h6{
    font-size: 12px;
}
.found{
    font-size: 10px;
}
.green{
    color: $color-c;
    font-size: 24px;
    font-weight: bolder;
}
.small{
    font-size: 12px;
}
</style>
