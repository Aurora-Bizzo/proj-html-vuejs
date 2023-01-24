<script>
import AppJumbotron from './sub-components/AppJumbotron.vue';

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
    <header>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    <img class="logo" src="../assets/img/dark-logo.png" alt="">
                </div>
                <div class="col-6">
                    <ul>
                        <li v-for="(item, index) in HeaderArray">
                            {{ item }} <i class="fa-solid fa-angle-down"></i>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <ul>
                        <li><i class="fa-brands fa-twitter"></i></li>
                        <li><i class="fa-brands fa-facebook-f"></i></li>
                        <li><i class="fa-brands fa-instagram"></i></li>
                        <li><i class="fa-brands fa-linkedin"></i></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
    <AppJumbotron/>
</template>

<style lang="scss" scoped>
@use 'src/styles/partials/variables' as *;

    header {
        width: 100%;
        padding: 25px 0 15px 0;
        position: fixed;
        top: 0;
        left: 0;
        transition: all 1s;
    }

    .logo {
        max-width: 158px;
    }

    ul {
        list-style-type: none;
        display: flex;
        padding: 0;
    };

    .col-6 {

        color: $meteorite;

        ul {
            justify-content: space-around;
            font-weight: 600;
        }

        i {
        font-size: 10px;
        }
    }

    .col-3 {

        ul {
            justify-content: flex-end;
        }

        li{
            margin-left: 25px;
        }

        i {
            font-size: 20px;
            color: $ebony-clay;
        }

    }


</style>