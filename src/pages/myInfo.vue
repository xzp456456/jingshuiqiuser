<template>
  <div>
    <header></header>
    <main>
      <div class="item">
        <div class="list">
          <div class="row">
            <div class="pull-left title">头像</div>
            <div class="pull-right headerImg">
              <img src="../assets/img/arar.png">
            </div>
          </div>
        </div>
        <div class="list">
          <div class="row">
            <div class="pull-left title">昵称</div>
            <div class="pull-right text_right">爱琴弦</div>
          </div>
        </div>
        <div class="list">
          <div class="row">
            <div class="pull-left title">手机号</div>
            <div class="pull-right text_right">18559782829</div>
          </div>
        </div>
        <div class="list">
          <div class="row">
            <div class="pull-left title">姓名</div>
            <div class="pull-right text_right">李彬彬</div>
          </div>
        </div>
        <div class="list">
          <div class="row">
            <div class="pull-left title">省市区</div>
            <div class="pull-right text_right">福建省厦门市集美区</div>
          </div>
        </div>
        <div class="list">
          <div class="row">
            <div class="pull-left title">装机地址</div>
            <div class="pull-right text_right">软件园三期A02</div>
          </div>
        </div>
      </div>
    </main>
    <footer></footer>
  </div>
</template>
<script>
export default {
  methods: {}
};
</script>
<style scoped="">
body {
  margin: 0 auto;
  padding: 0;
}

.pull-left {
  float: left !important;
}

.pull-right {
  float: right !important;
}

.headerImg {
  width: 1.25rem;
  height: 1.25rem;
  background: rgba(238, 238, 238, 1);
  border-radius: 50%;
  position: relative;
  top: 0.4rem;
}

.headerImg img {
  width: 100%;
}

.list {
  width: 100%;
  height: 2rem;
  border-bottom: 1px solid #e6e6e6;
  font-size: 0.42rem;
  font-family: PingFang-SC-Medium;
  font-weight: 500;
  color: rgba(51, 51, 51, 1);
}

.text_right {
  line-height: 2rem;
}

.row {
  width: 90%;
  margin: 0 auto;
}

.title {
  line-height: 2rem;
}
</style>
