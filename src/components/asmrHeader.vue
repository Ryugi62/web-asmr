<template>
  <div class="headerBox">
    <div class="menuButton">=</div>
    <div class="mainLogo">Hello Header</div>
    <div class="iconBox">
      <div class="subscribeBtn">구독하기</div>
      <div class="loginBtn">로그인</div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.headerBox {
  border-bottom: 1px solid black;
  background-color: inherit;
  height: 7%;
  display: flex;
  position: relative;
}

.menuButton {
  left: 1%;
  position: absolute;
}

.mainLogo {
  margin: auto;
}

.iconBox {
  right: 1%;
  display: flex;
  position: absolute;
}
</style>
