<script>
import VueKinesis from "vue-kinesis";
import { KinesisContainer, KinesisElement} from "vue-kinesis";

export default {
    VueKinesis,
    KinesisContainer,
    KinesisElement
}
</script>

<template lang="">
    <div class="jumbotron w-100">
        <div class="background"></div>
        <div class="container d-flex">
            <div class="col-6">
                <div class="content">
                    <div class="text">
                        <h5>I'M WINGMAN</h5>
                        <h1>Peace On Earth A Wonderful Wish But No Way</h1>
                        <p>Success isn't overnight. It's when everyday you get a little better than the day before. It all adds up.</p>
                    </div>
                    <div class="btn-div">
                        <button>Get Started For Free <i class="fa-solid fa-arrow-right"></i></button>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <div class="face-bg">
                    <img src="src\assets\img\home-movation-hero-image.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use 'src/styles/partials/mixin' as *;

.background {
    position: fixed;
    left: 0;
    right: 0;
    z-index: -1;
    height: 100%;
    display: block;
    background-color: #F6F6FD;
    background-image: url(https://maxcoach.thememove.com/main/wp-content/uploads/sites/1/2020/05/background-pattern-wavify.png);
}

.face-bg {
    background-image: url("src/assets/img/home-movation-shape-face.png");
    background-repeat: no-repeat;
    background-position: 0px 130px;
}

.container {
    position: fixed;
    left: 0;
    right: 0;
    z-index: 0;
    padding: 137px 0px 0px 0px;
}

p {
    margin-top: 25px;
    color: rgb(54, 54, 54);
}

h5 {
    margin-bottom: 10px;
    font-size: 16px;
    font-weight: 500;
}

h1 {
    font-size: 3.8rem;
    font-family: Gilroy;
    color: $vulcano;
}
.content {
    padding: 70px 15px 70px 15px;
}

.text {
    width: 440px
}

.btn-div {
    margin: 32px 0px 0px 0px;margin: 32px 0px 0px 0px;
}

button {
    @include btn-green;

    i {
        font-size: smaller;
        margin-left: 5px;
    }
}
    
</style>