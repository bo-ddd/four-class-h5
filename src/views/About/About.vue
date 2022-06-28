<template>
  <div class="about">
    <div class="main">
      <div class="flex-between main-header">
        <div class="flex-center main-leftarrow">
          <img
            class="icon-leftarrow"
            src="../../assets/images/leftarrow-white_icon.png"
            alt=""
          />
        </div>
        <div class="flex-center main-title">yolanda219</div>
        <div class="main-right"></div>
      </div>
      <div class="middle">
        <div class="middle-top flex-between">
          <div class="middle-top_text">
            <div>Yolanda</div>
            <div>Barrueco</div>
          </div>
          <div class="middle-top_picture flex-center">
            <img
              class="icon-headportrait"
              src="../../assets/images/headportrait_icon.jpg"
              alt=""
            />
          </div>
        </div>
        <div class="middle-bottom">Product designer @uigate</div>
      </div>
      <div class="comment">
        <div class="comment-title flex-between">
          <div class="comment-title_question" @click="questions">
            37 Questions
          </div>
          <div class="comment-title_answers" @click="answers">12 Answers</div>
        </div>
        <div class="comment-line flex">
          <div class="comment-line_question"></div>
          <div class="comment-line_answers"></div>
        </div>
        <div class="comment-content" v-if="isquestion">
          <div class="comment-content_item">
            <div class="item-title">
              <span>#ui</span>
              <span class="plr-7">#ux</span>
              <span>#interoction</span>
            </div>
            <div class="item-content">
              Why does YouTube disable the comment button until text has been
              entered
            </div>
            <div class="item-footer flex-between">
              <div class="flex">
                <div class="align-center">
                  <img
                    class="icon-message"
                    src="../../assets/images/message_icon.png"
                    alt=""
                  />
                  <div>12</div>
                </div>
                <div class="align-center">
                  <img
                    class="icon-heart"
                    src="../../assets/images/heart_icon.png"
                    alt=""
                  />
                  <div>176</div>
                </div>
              </div>
              <div>12k Views</div>
            </div>
          </div>
          <div class="comment-content_item">
            <div class="item-title">
              <span>#ui</span>
              <span class="plr-7">#ux</span>
              <span>#interoction</span>
            </div>
            <div class="item-content">
              Why does YouTube disable the comment button until text has been
              entered
            </div>
            <div class="item-footer flex-between">
              <div class="flex">
                <div class="align-center">
                  <img
                    class="icon-message"
                    src="../../assets/images/message_icon.png"
                    alt=""
                  />
                  <div>12</div>
                </div>
                <div class="align-center">
                  <img
                    class="icon-heart"
                    src="../../assets/images/heart_icon.png"
                    alt=""
                  />
                  <div>176</div>
                </div>
              </div>
              <div>12k Views</div>
            </div>
          </div>
          <div class="comment-content_item">
            <div class="item-title">
              <span>#ui</span>
              <span class="plr-7">#ux</span>
              <span>#interoction</span>
            </div>
            <div class="item-content">
              Why does YouTube disable the comment button until text has been
              entered
            </div>
            <div class="item-footer flex-between">
              <div class="flex">
                <div class="align-center">
                  <img
                    class="icon-message"
                    src="../../assets/images/message_icon.png"
                    alt=""
                  />
                  <div>12</div>
                </div>
                <div class="align-center">
                  <img
                    class="icon-heart"
                    src="../../assets/images/heart_icon.png"
                    alt=""
                  />
                  <div>176</div>
                </div>
              </div>
              <div>12k Views</div>
            </div>
          </div>
        </div>
        <div class="comment-content" v-if="isanswer">2</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isquestion: true,
      isanswer: false,
    };
  },
  methods: {
    questions() {
      this.isquestion = true;
      this.isanswer = false;
    },
    answers() {
      this.isquestion = false;
      this.isanswer = true;
    },
  },
};
</script>
<style scoped>
.about {
  background-color: #bec3d3;
}
.main {
  border-radius: 30px;
  background: -webkit-linear-gradient(#ff6464, #ffc384); /* Safari 5.1 - 6.0 */
  background: -o-linear-gradient(#ff6464, #ffc384); /* Opera 11.1 - 12.0 */
  background: -moz-linear-gradient(#ff6464, #ffc384); /* Firefox 3.6 - 15 */
  background: linear-gradient(
    #ff6464,
    #ffc384
  ); /* 标准的语法（必须放在最后） */
  height: 100vh;
  display: grid;
  grid-template-rows: 1fr 1.6fr 6fr;
  position: relative;  
}
.main-header {
  padding: 34px 36px;
}
.main-right {
  width: 3.6rem;
  height: 3.6rem;
}
.icon-leftarrow {
  width: 3.6rem;
  height: 3.6rem;
}
.main-leftarrow {
  border-radius: 50%;
  background-color: #d76958;
}
.main-title {
  color: #fee8db;
  font-size: 2rem;
}
.middle {
  padding: 0 36px;
}
.middle-top_text {
  color: #fff;
  font-size: 3rem;
  font-weight: bold;
}
.middle-top_picture {
  width: 8.8rem;
  height: 8.8rem;
  border-radius: 50%;
  background-color: #fff;
}
.icon-headportrait {
  width: 8.2rem;
  height: 8.2rem;
  border-radius: 50%;
}
.middle-bottom {
  color: #fee8db;
  font-size: 1.4rem;
  padding-bottom: 40px;
}
.comment {
  background-color: #fff;
  border-radius: 30px;
  position: absolute;
  bottom: 0;
  width: 100%;
}
.comment-title {
  padding: 30px 48px;
  font-size: 1.6rem;
}
.comment-line {
  padding: 1px 0;
  background-color: #ccc;
  width: 100%;
}
.comment-title_answers {
  color: #8e8e90;
}
.comment-line_question {
  background-color: #f67704;
  padding: 1px 0;
  width: 35%;
  margin: 0 36px;
}
.comment-line_answers {
  background-color: #ccc;
  padding: 1px 0;
  width: 35%;
  margin: 0 36px;
}
.comment-content {
  padding: 0 36px;
  height: 60vh;
  overflow-y: scroll;
}
.item-footer {
  font-size: 1.2rem;
  color: #bec3d3;
  padding: 26px 0;
  border-bottom: 1px solid #ccc;
}
.icon-message {
  width: 12px;
  height: 12px;
  padding-right: 6px;
}
.icon-heart {
  width: 12px;
  height: 12px;
  padding-right: 6px;
  padding-left: 36px;
}
.item-content {
  font-size: 1.8rem;
}
.item-title {
  padding-top: 44px;
  padding-bottom: 14px;
  font-size: 1.2rem;
  color: #75c8fc;
}
::-webkit-scrollbar {
  display: none;
}
</style>