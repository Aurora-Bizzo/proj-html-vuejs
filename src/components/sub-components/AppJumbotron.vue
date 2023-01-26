<script>

export default {
    
}
</script>

<template lang="">
    <div class="jumbotron w-100">
        <div class="container d-flex">
            <div class="col-4 padding">
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
            <div class="col-8">
                <div class="bg-rose d-flex justify-content-end">
                    <img src="src\assets\img\home-movation-hero-image.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/mixin' as *;


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
}
.padding {
    padding: 70px 15px 70px 0px;
}
.jumbotron {
    background-color: $amour;
    padding-top: 145px;
    background-image: url(https://maxcoach.thememove.com/main/wp-content/uploads/sites/1/2020/05/background-pattern-wavify.png);
}
.bg-rose {
    background-image: url(../../assets/img/home-movation-shape-face.png);
    background-position: top 150px left 290px;
    background-repeat: no-repeat;
}

button {
    @include btn-green;
}

button:hover {
    @include btn-green-hover;
}

</style>