<template>
    <section class="bg-hint py-5">
            <div class="container py-5">
                <h6 class="text-center">CHOOSE A COURSE AND GET STARTED</h6>
                <h2 class="text-center">Latest Featured <span class="green fw-lighter fs-3">Courses</span></h2>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <div class="d-flex card-on">
                            <img :src="'./img/course-02-480x298.jpg'" alt="full-hd" class="imgRound">
                            <div class="descrption ps-3">
                            <h4 class="green">$40.00</h4>
                            <h4 class="fs-5 fw-bold">Learning to write as a Professional Autor</h4>
                            <span><i class="fa-regular fa-file-lines "> 20 Lesson</i></span>
                            <span><i class="fa-regular fa-user"> 50 Student</i></span>
                        </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="d-flex card-on ">
                            <img :src="'./img/stock-full-hd-03-480x298.jpg'" alt="full-hd" class="imgRound">
                            <div class="descrption ps-3">
                            <h4 class="green">Free</h4>
                            <h4 class="fs-5 fw-bold">Customer-centric Info-Tech Strategies</h4>
                            <span><i class="fa-regular fa-file-lines"> 24 Lesson</i></span>
                            <span><i class="fa-regular fa-user"> 769 Student</i></span>
                        </div>
                        </div>
                    </div>
                    <div class="row mt-5">
                        <div class="col-6">
                            <div class="d-flex card-on">
                                <img :src="'./img/stock-full-hd-04-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 19.00</h4>
                                <h4 class="fs-5 fw-bold">Opening Programming Courses for Everyone: Pyton</h4>
                                <span><i class="fa-regular fa-file-lines"> 24 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 769 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex ms-3 card-on">
                                <img :src="'./img/stock-full-hd-06-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 26.00</h4>
                                <h4 class="fs-5 fw-bold">Academic Listening and Note-taking</h4>
                                <span><i class="fa-regular fa-file-lines"> 14 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 67 Student</i></span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row mt-5">
                        <div class="col-6">
                            <div class="d-flex card-on">
                                <img :src="'./img/course-featured-image-01-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 39.00</h4>
                                <h4 class="fs-5 fw-bold">Master in jQuery in a Short Period of Time</h4>
                                <span><i class="fa-regular fa-file-linesr"> 6 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 51 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="d-flex ms-3 card-on">
                                <img :src="'./img/stock-full-hd-05-480x298.jpg'" alt="full-hd" class="imgRound">
                                <div class="descrption ps-3">
                                <h4 class="green"> $ 59.00</h4>
                                <h4 class="fs-5 fw-bold">Introduction to Javascript for beginner</h4>
                                <span><i class="fa-regular fa-file-lines"> 14 Lesson</i></span>
                                <span><i class="fa-regular fa-user"> 76 Student</i></span>
                                </div>
                            </div>
                        </div>
                        <div class="text-center my-5"><button type="button" class="change color-btn">View all courses<i class="fa-solid fa-arrow-right px-2"></i></button></div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
    name:'AppCourses',
}
</script>

<style lang="scss">
@import "../styles/vars.scss";

.bg-hint{
    background-color: $hint;
}
.imgRound{
    width: 150px;
    height: 150px;
    border-radius:50%;

}
.card-on:hover{
 background-color: white;

}
.change:hover{
    background-color: white;
    color:$color-i;
    border-color:black;
}

.green{
    color: $color-c;
    font-size: 24px;
    font-weight: bolder;
}
i{
    font-size:10px;
    padding: 10px;
}
.color-btn{
    background-color: $color-c;
    padding: 10px;
    border-radius: 10px;
    color: white;
}

</style>