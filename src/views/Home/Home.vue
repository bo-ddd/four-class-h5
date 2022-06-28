<template>
<div class="bgc">
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
                <div class="main-tep">
                    <div class="tep-one">
                        <div class="tep-text">
                            <div class="blue-text">#ui #ux #intoroction</div>
                            <div class="bold-text main-text">Why do people clear the screen multiple times when using a
                                calculator?</div>
                            <div class="main-answers flex-center">
                                <div class="answer-text">10 answers</div>
                                <div class="answer-text">12k views</div>
                            </div>
                            <div class="icon_person flex-center">
                                <img class="icon mr-10" src="../../assets/images/icon_headsculpture.jpg" alt="">
                                <div class="">
                                    <div class="bold-text user-text">Donot Twerski</div>
                                    <div class="info-text">UK dessigret update</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="tep-two">
                        <div class="tep-text">
                            <div class="blue-text">#ui #ux #intoroction</div>
                            <div class="bold-text main-text">Why do people clear the screen multiple times when using a
                                calculator?</div>
                            <div class="main-answers flex-center">
                                <div class="answer-text">10 answers</div>
                                <div class="answer-text">12k views</div>
                            </div>
                            <div class="icon_person flex-center">
                                <img class="icon mr-10" src="../../assets/images/icon_headsculpture.jpg" alt="">
                                <div class="">
                                    <div class="bold-text user-text">Donot Twerski</div>
                                    <div class="info-text">UK dessigret update</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
        </div>
    </div>
        <div class="home-footer">
            <div class="flex-between">
                <img class="icon-size"  src="../../assets/images/sort.png" alt="">
                <img class="icon-size" src="../../assets/images/search.png" alt="">
                <img class="icon-size" src="../../assets/images/add.png" alt="">
                <img class="icon-size" src="../../assets/images/like.png" alt="">
                <img class="icon-size" src="../../assets/images/mine.png" alt="">
            </div>
        </div>
</div>
</template>
<style scoped>

.tep-one,.tep-two{
    background-color: #fff;
    border-radius: 2rem;
    position: absolute;
    left: 0;
    top: 0;
    transition: transform 1s;
}
.tep-two{
    top: 2rem;
}
.main-tep:hover .tep-one{
    transform:translateY(5rem);
}
.bgc{
    background: #ccc;
}
.home{
    height: 100vh;
    padding: 3.6rem;
    background: linear-gradient(#316be9,#d0c6f8,#f4e8dc);
    border-radius: 4rem 4rem 0 0;
}
.trend-text {
  font-size: 2rem;
}
.question-text {
  font-size: 3.5rem;
}
.main-title {
  font-size: 1rem;
  border-radius: 4rem;
  padding: 0.8rem 6rem;
  background: #566aa9;
  margin: 2.6rem 0 1.2rem 0;
}
.main-tep{
    position: relative;
    /* background-color: #fff; */
    /* border-radius: 2rem; */
    height: 35rem;
}
.tep-text{
    margin: 3.5rem;
    background: url('../../assets/images/Q.png') no-repeat;
    background-size: 10rem;
    background-position: 13rem 20rem;
}
.blue-text,.answer-text,.user-text,.info-text{
   font-size: 1.2rem;
   /* margin: 2rem 0; */
}
.blue-text{
    color: #65bffb;
    margin: 2rem 0;
}
.main-text{
    font-size: 2rem;
    margin-bottom: 3.4rem;
}
.main-answers{
    margin-bottom: 11.6rem;
}
.answer-text{
    color: #d1d8de;
    margin-right: 3rem; 
}
.icon {
    width: 3.7rem;
    height:3.7rem;
    border-radius: 5rem;
}
.home-footer{
    padding: 2.6rem 3.5rem;
    background: #fff;
    border-radius: 0 0 4rem 4rem;
}
.icon-size{
    width: 2.2rem;
    height: 2.2rem;
}
</style>