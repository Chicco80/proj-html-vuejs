<template>
<div>

        <div class="container number">
            <div class="row justify-content-center text-center">
                <div class="col-2">
                    <p class="green fs-2">1.926</p>
                    <p class="small">FINISHED SESSION</p>
                </div>
                <div class="col-2">
                    <p class="green fs-2">3.092+</p>
                    <p class="small">ENROLLED LEANERS</p>
                </div>
                <div class="col-2">
                    <p class="green fs-2">200</p>
                    <p class="small">ONLINE INSTRUCTION</p>
                </div>
                <div class="col-2">
                    <p class="green fs-2">100%</p>
                    <p class="small">SATISFACTION RATE</p>
                </div>
            </div>
        </div>
        <!-- fine sez. numeri -->

        <!-- card asimmetriche -->
        <div class="container my-5 pb-5 cont-pos ">
            <div class="row ">
                <div class="col-3 ">
                    <div class="card card-h box-shadow" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="fw-bold">Graphic Design</h5>
                            <p class="card-text">Have a passion for graphics and arts? Show your talent with confidence and self-assertiveness.</p>
                        </div>
                        <img :src="'./img/home-6-service-image-01.png'" class="card-img-top" alt="img01">
                    </div>
                </div>
                <div class="col-3 ">
                    <div class="card card-h mb-3 img-one box-shadow" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="fw-bold">Businnes Administration</h5>
                            <p class="card-text">Learners and encouraged to study the mechanism and structure of sistem administration.</p>
                        </div>
                        <img :src="'./img/home-6-service-image-02.png'" class="card-img-top" alt="img01">
                    </div>
                </div>
                <div class="col-4">
                    <div class="card check box-shadow" style="width: 26rem;">
                        <div class="card-body">
                            <h6 class="card-subtitle mb-2 text-muted">TOGETHER WE CAN CREATE</h6>
                            <h5 class="card-title font">Service We <span class="green fs-2 fw-lighter">Can Provide</span> For My Client</h5>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Select & customize courses to your preference</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Change the tutor and make arrangement</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Partecipate in event to join others</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Get teh desired certificate delivered at house</p>
                            <button type="button" class="btn btn s-change">Get started for free</button>
        
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-3">
                        <div class="card card-h mt-4 box-shadow" style="width: 18rem;">
                            <img :src="'./img/home-6-service-image-03.png'" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="fw-bold">Idea Discussion</h5>
                            <p class="card-text">Get teamed up with the specialist who work and teach coding for years at famous university.</p>
                        </div>
                        </div>
                    </div>
                    <div class="col-3 ms-1">
                        <div class="card card-h img-two box-shadow" style="width: 18rem;">
                            <img :src="'./img/home-6-service-image-04.png'" class="card-img-top mt-5 pt-5" alt="...">
                        <div class="card-body mt-4 pt-4">
                            <h5 class="fw-bold">Web Developement</h5>
                            <p class="card-text">Learn to star building a webpage for scratch.you decide your own peace, course and speed.</p>
                        </div>
                        </div>
                    </div>
                </div>
            </div>
    </div>
</div>
</template>

<script>
export default {
    name:'AppCol',
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";


.card-h{
    height: 500px;
}
.cont-pos{
    position: relative;

}
.box-shadow{
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
.img-one{
    position: absolute;
    top: 5%;
}
.img-two{
    position: absolute;
    top: 54%;
}
.font{
    font-size: 32px;
    font-weight: bolder;
}
.check{
    position: absolute;
    top: 35%;
}
.btn{
    background-color: $color-c;
    color:white;
}
.s-change:hover{
    background-color: $color-i;
    color:white;
    border-color:$color-i ;
}
.green{
    color: $color-c;
    font-size: 24px;
    font-weight: bolder;
}

</style>