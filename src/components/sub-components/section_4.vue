<script>
export default {

}
</script>

<template lang="">
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="margin-13 text-center">
                    <h3>BEGIN YOUR JOURNEY AT MAXCOACH</h3>
                </div>
                <div class="text-center">
                    <h2>Latest <span>Online Courses</span></h2>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="row">
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-1 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$30.00</div>
                                <h3 class="text">How to be Successful: Create A Growth Mindset For Success</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 3 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-2 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$30.00</div>
                                <h3 class="text">How to Build Confidence in Your Abilities</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 1 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-3 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$20.00</div>
                                <h3 class="text">Productivity Machine – Focus in a Distracted World</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 5 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-4 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$20.00</div>
                                <h3 class="text">Effective Time Management Mastery – Complete Guide</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 18 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-5 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$25.99</div>
                                <h3 class="text">Body Language Secrets for Entrepreneurs</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 19 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="card" style="width: 23.125rem;">
                            <div class="wrapper w-100">
                                <div class="card-plain img-6 d-flex justify-content-center align-items-center w-100 h-100"></div>
                            </div>
                            <div class="card-body">
                                <div class="price">$19.99</div>
                                <h3 class="text">Management Skills: The Science of Leadership</h3>
                                <div class="ls">
                                    <span><i class="fa-regular fa-file-lines"></i> 17 Lessons</span>
                                    <span class="ps-3"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="d-flex justify-content-center">
                    <button>View all courses <i class="fa-solid fa-arrow-right"></i></button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/mixin' as *;

.card:hover {
    box-shadow: 0  0 25px 3px rgb(208, 208, 208);
}
.ls span {
    color: rgba(105, 105, 105, 0.81);
} 

.text {
    font-size: 17px;
    line-height: 1.6;
    color:#3F3A64;
    font-weight: 700;
}

.text:hover {
    color:#26aa94;
}

.price {
    font-family: Gully;
    font-size: 28px;
    color:#26aa94;
}

.card-body {
    padding: 30px 30px 38px;
}
.card {
    margin: 0 27px 30px 27px;
}

.wrapper {
    overflow: hidden;
    height: 229.6px;
}

.card-plain {
    background-position: center;
    transition: all 2s ease;
    border-radius: 0.375rem 0.375rem 0 0;
    background-size: cover;
}

.img-1 {
    background-image: url(../../assets/img/motivation-course-06-480x298.jpg);
}

.img-2 {
    background-image: url(../../assets/img/motivation-course-05-480x298.jpg);
}

.img-3 {
    background-image: url(../../assets/img/motivation-course-04-480x298.jpg);
}

.img-4 {
    background-image: url(../../assets/img/motivation-course-03-480x298.jpg);
}

.img-5 {
    background-image: url(../../assets/img/motivation-course-02-480x298.jpg);
}

.img-6 {
    background-image: url(../../assets/img/motivation-course-01-480x298.jpg);
}

.card-plain:hover {
    transform: scale(1.1)
}
.container {
    padding: 155px 0 100px 0;
}

h3 {
    font-size: 15px;
    font-weight: 500;
    letter-spacing: 2px;
    color: rgba(105, 105, 105, 0.81);
}

.margin-13 {
    margin-bottom: 13px;
}

h2 {
    font-family: Gully;
    font-size: 48px;
    font-weight: 400;
    line-height: 1.34em;
    color: #3F3A64
}

span {
    font-family: Gully;
    color:#26aa94;
}

button {
    @include btn-green;
}

button:hover {
    @include btn-green-hover;
}

</style>