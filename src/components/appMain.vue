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
        <div class="container number">
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
        <div class="container my-5">
            <div class="row">
                <div class="col-3 ">
                    <div class="card mb-3" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="fw-bold">Graphic Design</h5>
                            <p class="card-text">Have a passion for graphics and arts? Show your talent with confidence and self-assertiveness.</p>
                        </div>
                        <img :src="'./img/home-6-service-image-01.png'" class="card-img-top  imgOne" alt="img01">
                    </div>
                </div>
                 <div class="col-3 ">
                    <div class="card mt-5" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="fw-bold">Businnes Administration</h5>
                            <p class="card-text">Learners and encouraged to study the mechanism and structure of sistem administration.</p>
                        </div>
                        <img :src="'./img/home-6-service-image-02.png'" class="card-img-top" alt="img01">
                    </div>
                </div>
                <div class="col-3">
                    <div class="card check" style="width: 26rem;">
                        <div class="card-body">
                            <h6 class="card-subtitle mb-2 text-muted">TOGETHER WE CAN CREATE</h6>
                            <h5 class="card-title font">Service We <span class="green fs-2 fw-lighter">Can Provide</span> For My Client</h5>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Select & customize courses to your preference</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Change the tutor and make arrangement</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Partecipate in event to join others</p>
                            <p class="card-text fs-6"><i class="fa-solid fa-check green fs-6"></i>Get teh desired certificate delivered at house</p>
                            <button type="button" class="btn btn-success">Get started for free</button>
        
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-3">
                        <div class="card" style="width: 18rem;">
                            <img :src="'./img/home-6-service-image-03.png'" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="fw-bold">Idea Discussion</h5>
                            <p class="card-text">Get teamed up with the specialist who work and teach coding for years at famous university.</p>
                        </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="card mt-5" style="width: 18rem;">
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
        <section class="grey">
            <div class="container grey py-5">
                <h6 class="text-center">CHOOSE A COURSE AND GET STARTED</h6>
                <h2 class="text-center">Latest Featured <span class="green fw-lighter ">Courses</span></h2>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <div class="d-flex">
                            <img :src="'./img/stock-full-hd-03-480x298.jpg'" alt="full-hd" class="imgRound">
                            <div class="descrption ps-3">
                            <h4 class="green">$40.00</h4>
                            <h4 class="fs-5 fw-bold">Learning to write as a Professional Autor</h4>
                            <span><i class="fa-regular fa-user"> 20 Lesson</i></span>
                            <span><i class="fa-regular fa-user"> 50 Student</i></span>
                        </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="d-flex">
                            <img :src="'./img/stock-full-hd-03-480x298.jpg'" alt="full-hd" class="imgRound">
                            <div class="descrption ps-3">
                            <h4 class="green">Free</h4>
                            <h4 class="fs-5 fw-bold">Customer-centric Info-Tech Strategies</h4>
                            <span><i class="fa-regular fa-user"> 24 Lesson</i></span>
                            <span><i class="fa-regular fa-user"> 769 Student</i></span>
                        </div>
                        </div>
                    </div>
                    <div class="row mt-5">
                        <div class="col-6">
                            <div class="d-flex">
                                <img :src="'./img/stock-full-hd-04-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 19.00</h4>
                                <h4 class="fs-5 fw-bold">Opening Programming Courses for Everyone: Pyton</h4>
                                <span><i class="fa-regular fa-user"> 24 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 769 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex">
                                <img :src="'./img/stock-full-hd-06-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 26.00</h4>
                                <h4 class="fs-5 fw-bold">Academic Listening and Note-taking</h4>
                                <span><i class="fa-regular fa-user"> 14 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 67 Student</i></span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-5">
                        <div class="col-6">
                            <div class="d-flex">
                                <img :src="'./img/stock-full-hd-04-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 39.00</h4>
                                <h4 class="fs-5 fw-bold">Masrer in jQuery in a Short Period of Time</h4>
                                <span><i class="fa-regular fa-user"> 6 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 51 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex">
                                <img :src="'./img/stock-full-hd-05-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 59.00</h4>
                                <h4 class="fs-5 fw-bold">Introduction to Javascript for beginner</h4>
                                <span><i class="fa-regular fa-user"> 14 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 76 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="text-center my-5"><button type="button" class="btn btn-success ">View all courses<i class="fa-regular fa-arrow-right-long"></i></button></div>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="container text-center">
                <h2>Why People Talk About <span class="green fw-lighter fs-2">MaxCoach</span>? </h2>
            </div>
            <div class="container">
            <div class="row mt-5">
                <div class="col">
                    <div class="d-flex justify-content-center">
                        <img :src="'./img/testimonial-avata-02.jpg'" alt="full-hd" class="imgRound ml-3">
                        <div class="descrption ps-3 w-50 fs-3 mx-3">
                            <p>I am free at my own peace,follow my own schedule and choose the subject I like. Great study portal for people like me</p>
                            <h6>MINA HOLLACE</h6>
                            <p class="fs-6">/Freelancer</p>    
                        </div>
                    </div>
                </div>
            </div>
            </div>
            <div class="container my-5">
                <ul class="d-flex justify-content-center align-items-center ">
                    <li class="mx-3"><img :src="'./img/client-logo-colored-01.png'" alt="aqua"></li>
                    <li class="mx-3"><img :src="'./img/client-logo-colored-02.png'" alt="adroll"></li>
                    <li class="mx-3"><img :src="'./img/client-logo-colored-03.png'" alt="firefox"></li>
                    <li class="mx-3"><img :src="'./img/client-logo-colored-04.png'" alt="woodland"></li>
                    <li class="mx-3"><img :src="'./img/client-logo-colored-05.png'" alt="bullfit"></li>
                    <li class="mx-3"><img :src="'./img/client-logo-colored-06.png'" alt="sixbase"></li>
                </ul>
            </div>
        </section>
        <section>
            <div class="container text-center">
                <h6 class="mt-5">ENJOY READING ON MAXCOACH</h6>
                <h2>Latest on <span class="green fw-lighter">Our Blogs</span></h2>
            </div>
            <div class="container my-5">
            <div class="row py-5">
                <div class="col-4">
                    <div class="card" style="width: 25rem;">
                        <img :src="'./img/artist-blog-03-480x325.jpeg'" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h6 class="card-title">Artist</h6>
                            <p class="card-text fw-bold">Brush Strokes Energize Trees in<br/> Painting</p>
                            <span><i class="fa-regular fa-calendar"> May 15,2020</i></span>
                            <span><i class="fa-regular fa-eye"> 688 views</i></span>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card" style="width: 25rem;">
                        <img :src="'./img/artist-blog-01-480x325.jpg'" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h6 class="card-title">Artist</h6>
                            <p class="card-text fw-bold">Pocket-Sized Notebook Hold Miniature Paintings</p>
                            <span><i class="fa-regular fa-calendar"> May 15,2020</i></span>
                            <span><i class="fa-regular fa-eye"> 603 views</i></span>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="card" style="width: 25rem;">
                        <img :src="'./img/artist-blog-02-480x325.jpg'" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h6 class="card-title">Artist</h6>
                            <p class="card-text fw-bold">Connection Between Self-<br/>Portraits and Identity</p>
                            <span><i class="fa-regular fa-calendar"> May 15,2020</i></span>
                            <span><i class="fa-regular fa-eye"> 688 views</i></span>
                        </div>
                    </div>
                </div>
            </div>
            </div>
        </section>
        <section>
            <div class="container my-5 text-center">
                <h6>WANNA TRASFORM YOUR LIFE?</h6>
                <h2>Glad to <span class="green fw-lighter">Help You</span> Learn</h2>
            </div>
            <div class="container">
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
            <div class="container text-center">
                <img :src="'./img/home-6-services-image-1024x411.png'" alt="jumbo" class="jumbo">
                <h5>Start today for getting <span class="green fw-lighter">Online Certification</span></h5>
                <h2>You can be own guiding star with our help!</h2>
                <button type="button" class="btn btn-success px-5 mb-5">Get started now</button>
            </div>

        </section>
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
.imgOne{
    margin-top:124px
}
.font{
    font-size: 32px;
    font-weight: bolder;
}
.check{
    margin-top: 300px;
}
.grey{
 background-color:white;
}
.imgRound{
    width: 150px;
    height: 150px;
    border-radius:50%;

}
.jumbo{
    margin-bottom: 50px;
}
</style>
