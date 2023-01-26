<script>
export default {
    
}
</script>

<template lang="">
    <div class="container">
        <div class="row">
            <div class="col-3 d-flex align-items-center">
                <div class="w-1">
                    <img src="src\assets\img\background-pattern-grid-line-06.png" alt="">
                </div>
                <div class="calc">
                    <h2>1.926</h2>
                    <div>FINISHED SESSIONS</div>
                </div>
                <div class="w-1">
                    <img src="src\assets\img\background-pattern-grid-line-06.png" alt="">
                </div>
            </div>
            <div class="col-3 d-flex flex-column justify-content-center">
                <div>
                    <h2>100%</h2>
                    <div>SATISFACTION RATE</div>
                </div>
            </div>
            <div class="col-3 d-flex align-items-center">
                <div class="w-1">  
                    <img src="src\assets\img\background-pattern-grid-line-06.png" alt="">
                </div>
                <div class="calc-2">
                    <h2>3092+</h2>
                    <div>ENROLLED LEARNERS</div>
                </div>
            </div>
            <div class="col-3 d-flex align-items-center">
                <div class="w-1">
                    <img src="src\assets\img\background-pattern-grid-line-06.png" alt="">
                </div>
                <div class="calc">
                    <h2>200</h2>
                    <div>ONLINE INSTRUCTORS</div>
                </div>
                <div class="w-1">
                    <img src="src\assets\img\background-pattern-grid-line-06.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../styles/partials/variables' as *;
.container {
    text-align: center;
    padding: 132px 15px 82px 15px;
}

.w-1 {
    width: 1px;
}

.calc {
    width: calc(100% - 2px);
}

.calc-2 {
    width: calc(100% - 1px);
}

h2 {
    font-family: Gilroy;
    font-size: 40px;
    font-weight: 600;
    color: $jungle-green;
}

</style>