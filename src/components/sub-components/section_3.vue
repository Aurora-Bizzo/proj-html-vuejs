<script>
export default {
    
}
</script>

<template lang="">
    <div class="container">
        <div class="row">
            <div class="col-7">
                <div class="wrapper">
                    <div class="video d-flex justify-content-center align-items-center">
                        <img src="src\assets\img\icon-youtube-play.png" alt="">
                    </div>
                </div>
            </div>
            <div class="col-5">
                <div class="h-100 d-flex flex-column justify-content-center">
                    <div>
                        <h3 class="margin-54-176">
                        "Every morning you have two choices: continue to sleep with your dreams, or wake up and chase them."
                        </h3>
                    </div>
                    <div class="margin-25">
                        <img class="size-30x22" src="src\assets\img\home-movation-shape-01.png" alt="">
                    </div>
                    <div>
                        <h3 class="purple">Kaixa Stark</h3>
                    </div>
                    <div>
                        <h4>
                            WINGMAN
                        </h4>
                    </div>
                </div>
            </div>
        </div> 
    </div>
</template>

<style lang="scss" scoped>

.wrapper {
    height: 450px;
    width: 670px;
    overflow: hidden;
}
.video {
    width: 670px;
    height: 450px;
    background-position: center;
    background-image: url(../../assets/img/home-movation-video-poster-670x450.jpg);
    transition: all 2s ease;
}

img {
    width: 100px;
    height: 70px;
    transition: all 2s ease;
}
.video:hover {
    transform: scale(1.1)
}

.video:hover img {
    transform: scale(0.8)
}

.margin-54-176 {
    margin: 0 176px 54px 0;
    font-family: Gilroy;
    line-height: 2.5rem;
}

.size-30x22 {
    width: 30px;
    height: 22px;
}

.purple {
    font-size: 21px;
    font-weight: 600;
    color: #3F3A64;
}

h4 {
    font-size: 12px;
    font-weight: 500;
    line-height: 1.5em;
    letter-spacing: 1.38px;
    color: #8C89A2;
}

.margin-25 {
    margin-bottom: 25px;
}

</style>