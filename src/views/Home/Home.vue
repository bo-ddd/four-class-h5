<template>
    <div class="home">
        <div class="home-header">
            <div class="text trend-text">Trending</div>
            <div class="flex-center">
                <div class="text question-text">Questions</div>
                <img src="../../assets/images/icon_downarrow.png" alt="">
            </div>
        </div>
        <div class="home-main">
            <div class="text main-title">Swipe left/right to check more</div>
        </div>
        <div class="home-footer"></div>
    </div>
</template>
<style scoped>



.home{
    height: 100vh;
    padding: 3.6rem;
    background: linear-gradient(#316be9,#d0c6f8,#f4e8dc);
}
.trend-text{
    font-size: 2rem;
}
.question-text{
    font-size: 3.5rem;
}
.main-title{
    font-size: 1rem;
    border-radius: 4rem;
    padding: 0.8rem 6rem;
    background: #566aa9;
}

</style>