<script>
export default {
    
}
</script>

<template lang="">
    <div class="container">
        <div class="row">
            <div class="col-4">
                <h3>BOOK STORE ONLINE</h3>
                <h2>Be Alpha With<span> Wingman's Book</span></h2>
                <div>
                    <ul>
                        <li><i class="fa-solid fa-check"></i>Help you understand yourself better</li>
                        <li><i class="fa-solid fa-check"></i>Revealing mature tips</li>
                        <li><i class="fa-solid fa-check"></i>Give the right advice</li>
                        <li><i class="fa-solid fa-check"></i>Fascinating examples of alpha man</li>
                    </ul>
                </div>
                <div>
                    <button>Get Free Ebook</button>
                </div>
            </div>
            <div class="col-8">
                <div class="h-100 d-flex">
                    <div class="section h-100 justify-content-around">
                        <div class="img-block">
                            <img src="src\assets\img\product-book-11-400x400.jpg" alt="">
                        </div>
                        <div class="d-flex flex-column align-items-center w-100">
                            <div class="title">Alpha man by Maxcoach</div>
                            <div class="price">29.00$</div>
                        </div>
                    </div>
                    <div class="section h-100">
                        <div class="img-block">
                            <img src="src\assets\img\product-book-10-400x400.jpg" alt="">
                        </div>
                        <div class="d-flex flex-column align-items-center w-100">
                            <div class="title">Real man 4.0 by Maxcoach</div>
                            <div class="price">39.00$</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/mixin' as *;

.price {
    font-size: 25px;
    font-weight: 600;
    color: #26aa94;
}

img {
    width: 330px;
}

.title {
    font-size: 20px;
    font-weight: 500;
    color: #3F3A64;
}
.img-block {
    height: 330px;
}

.section {
    width: 330px;
    background-color: #f5f5f5;
}

.col-8 {
    padding-left: 100px
}

h3 {
    font-size: 15px;
    font-weight: 500;
    line-height: 2em;
    letter-spacing: 2px;
    color: #333333;
    margin-bottom: 8px;
}

h2 {
    font-family: Gully;
    font-size: 40px;
    font-weight: 400;
    line-height: 1.5em;
    color: #3F3A64;

    span {
        color:#26aa94;
        font-family: Gully;
    }
}

ul {
    list-style-type: none;
    color: #9D9D9D;
    margin: 30px 0 40px 0;
    padding: 0;
    line-height: 2.5rem;

    i {
        color:#26aa94;
        margin-right: 15px;
    }
}

button {
    @include btn-green;
}

button:hover {
    @include btn-green-hover;
}

</style>