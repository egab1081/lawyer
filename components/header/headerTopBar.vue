<template>
  <div class="top-header">
    <div class="top-header_inner">
      <div class="left">
        <div class="left-left">
          <div class="image">
            <img src="~/assets/curcle.png" alt />
            <h2>C</h2>
          </div>
          <h1>
            СОЮЗ
            <br />АРБИТРАЖНЫХ <br />УПРАВЛЯЮЩИХ
          </h1>
        </div>
        <div class="left-right">
          <div>
            <img src="~/assets/locate.png" alt />
          </div>
          <div>
            <h2>Адрес компании:</h2>
            <span>г.Пермь, ул.</span>
            <br />
            <span>Екатерининская 120а</span>
          </div>
        </div>
      </div>
      <div class="right">
        <div class="right-left">
          <div class="phone-icon">
            <img src="~/assets/call.png" alt />
          </div>
          <div>
            <span class="phone-number">8 (800) 000 00 00</span>
            <h2>Заказать звонок</h2>
          </div>
        </div>
        <div class="right-right">
          <div class="burger"></div>
          <div class="burger"></div>
          <div class="burger"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script></script>
<style lang="scss" s scoped>
.top-header {
  display: flex;
  justify-content: center;
}
.top-header_inner img {
  margin-right: 20px;
}
.top-header_inner h2 {
  font-size: 17px;
  font-weight: normal;
}
.top-header_inner {
  margin-top: 5vh;
  display: flex;
  flex-direction: row;
  justify-content: center;
  color: #fff;
}
.headerTopBar {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.image {
  position: relative;
}
.image h2 {
  position: absolute;
  top: 12px;
  left: 25px;
  width: 100%;
  font-size: 51px;
  color: #fff;
  margin: 0;
  font-weight: normal;
}

.left {
  display: flex;
  flex-direction: row;
}
.left-left {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-right: 5vw;
}
.left-left h1 {
  font-size: 16px;
  font-weight: normal;
}
.left-right {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-right: 10vw;
}
.left-right span {
  font-size: 18.5px;
  white-space: nowrap;
}
.left-right h2 {
  text-decoration: underline;
  font-weight: normal;
}
.right {
  display: flex;
  flex-direction: row;
}
.right-left {
  margin-right: 5vw;
  display: flex;
  flex-direction: row;
}
.right-left h2 {
  text-decoration: underline;
  text-align: right;
  font-weight: normal;
}

.phone-number {
  font-size: 24px;
}
.phone-icon {
  margin-top: 5px;
}
.burger {
  width: 25px;
  height: 3px;
  background-color: #fff;
  margin: 5px 0;
}
</style>
