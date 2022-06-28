<template>
  <div class="home">
    <div class="home-header">
      <div class="text trend-text">Trending</div>
      <div class="flex-center">
        <div class="text question-text">Questions</div>
        <img src="../../assets/images/icon_downarrow.png" alt="" />
      </div>
    </div>
    <div class="home-main">
      <div class="text main-title">Swipe left/right to check more</div>
      <div class="main-tep">
        <div class="tep-text">
          <div class="blue-text">#ui #ux #intoroction</div>
          <div class="bold-text main-text">
            Why do people clear the screen multiple times when using a
            calculator?
          </div>
          <div>
            <div>10 answers</div>
            <div>12k views</div>
          </div>
        </div>
      </div>
    </div>
    <div class="home-footer"></div>
  </div>
  <div class="home-main">
    <div class="text main-title">Swipe left/right to check more</div>
    <div class="main-tep">
      <div class="tep-text"></div>
    </div>
  </div>
  <div class="home-footer">111111</div>
</template>
<style scoped>
.home {
  height: 100vh;
  padding: 3.6rem;
  background: linear-gradient(#316be9, #d0c6f8, #f4e8dc);
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
.tep-text {
  background: #fff;
  border-radius: 2rem;
  padding: 5rem 3.5rem 3.5rem 3.5rem;
}
.blue-text {
  color: #65bffb;
  font-size: 1.2rem;
}
.main-text {
  font-size: 2rem;
}
</style>