<script>
import AppJumbotron from './sub-components/AppJumbotron.vue'
export default {
    components: {
        AppJumbotron
    },
    data(){
        return{ 
        HeaderArray: [
                'Home', 'Pages', 'Courses', 'Features', 'Blog', 'Shop' 
            ],
        }
    }
}
</script>

<template lang="">
     <header class="vw-100">
        <div class="container h-100">
            <div class="row h-100">
                <div class="col-3 d-flex align-items-center">
                    <img src="src\assets\img\dark-logo.png" alt="">
                </div>
                <div class="col-6">
                    <ul class="h-100 d-flex justify-content-evenly align-items-center meteorite">
                        <li v-for="(item, index) in HeaderArray">
                            {{ item }} <i class="fa-solid fa-angle-down arrow"></i>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <ul class="h-100 d-flex align-items-center justify-content-end">
                        <li><i class="fa-brands fa-twitter"></i></li>
                        <li><i class="fa-brands fa-facebook-f ps-4"></i></li>
                        <li><i class="fa-brands fa-instagram ps-4"></i></li>
                        <li><i class="fa-brands fa-linkedin ps-4"></i></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
    <AppJumbotron/>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

header {
    height: 100px;
    position: absolute;
}

img {
    width: 158px;
}
    
ul {
    list-style-type: none;
}

.arrow {
    font-size: 10px;
}

i {
    font-size: 19px;
}

.meteorite {
    color: $meteorite;
    font-weight: 500;
}
</style>