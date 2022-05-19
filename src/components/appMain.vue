<template>
            <!-- partner -->
    <div>
        <section>
            <div class="container text-center py-5">
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
            <!-- fine partner -->

            <!-- artisti -->
        <section class="bg-hint py-5">
            <div class="container text-center">
                <h6 class="mt-5">ENJOY READING ON MAXCOACH</h6>
                <h2>Latest on <span class="green fw-lighter fs-2">Our Blogs</span></h2>
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
    </div>
</template>

<script>
export default {
    name: 'AppMain',
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";


.bg-hint{
    background-color: $hint;
}

.green{
    color: $color-c;
    font-size: 24px;
    font-weight: bolder;
}
.small{
    font-size: 12px;
}

.grey{
 background-color:white;
}



.change:hover{
    background-color: white;
    color:$color-i;
    border-color:black;
}
.s-change:hover{
    background-color: $color-i;
    color:white;
    border-color:$color-i ;
}

</style>
