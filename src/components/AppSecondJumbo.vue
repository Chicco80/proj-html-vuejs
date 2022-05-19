<template>
    <div>
         <section>
            <!-- fine artisti -->

            <!-- sezione icone -->
            <div class="container my-5 text-center">
                <h6>WANNA TRASFORM YOUR LIFE?</h6>
                <h2>Glad to <span class="green fw-lighter fs-2">Help You</span> Learn</h2>
            </div>
            <div class="container ">
                <div class="row my-5">
                    <div class="col-3">
                        <i class="fa-regular fa-flag fs-1"></i> 
                        <h5 class="my-1">Idea Discussion</h5> 
                        <p>Get teamed up with specialist who work and teach coding for years at famous universites</p>
                    </div>
                    <div class="col-3">
                        <i class="fa-solid fa-gear fs-1"></i>
                        <h5 class="my-1">Web Developement</h5> 
                        <p>Learn to start building a webpage from scratch. you decide your own peace, course and speed.</p>
                    </div>
                    <div class="col-3">
                        <i class="fa-regular fa-life-ring fs-1"></i> 
                        <h5 class="my-1">Sistem Administration</h5> 
                        <p>Learners are encouraged to study the mechanism and structure of system administration</p>
                    </div>
                    <div class="col-3"> 
                        <i class="fa-solid fa-tv fs-1"></i>
                        <h5 class="my-1">Graphi Design</h5> 
                        <p>Have a passion for a graphic and art? Show your talent with confidence and self-asseriveness</p>
                    </div>
                </div>
            </div>
            <!-- fine icone -->

            <!-- ultimo jumbo -->
            <div class="container text-center">
                <img :src="'./img/home-6-services-image-1024x411.png'" alt="jumbo" class="jumbo">
                <h5>Start today for getting <span class="green fw-lighter">Online Certification</span></h5>
                <h2>You can be own guiding star with our help!</h2>
                <button type="button" class="btn btn-success px-5 mb-5 change">Get started now</button>
            </div>

        </section>

    </div>
</template>

<script>
export default {
    name:'AppSecondJumbo',
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";



.jumbo{
    margin-bottom: 50px;
}
.green{
    color: $color-c;
    font-size: 24px;
    font-weight: bolder;
}
.change:hover{
    background-color: white;
    color:$color-i;
    border-color:black;
}
</style>