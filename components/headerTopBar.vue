<template>
  <div class="headerTopBar">
    <div class="left">
      <div class="left-left">
        <div class="image">
          <img src="assets/curcle.png" alt />
          <h2>C</h2>
        </div>
        <h1>
          СОЮЗ
          <br />АРБИТРАЖНЫХ
          <br />УПРАВЛЯЮЩИХ
        </h1>
      </div>
      <div class="left-right">
        <div>
          <img src="assets/locate.png" alt />
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
          <img src="assets/call.png" alt />
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
</template>
<script>
</script>
<style scoped>
.image {
  position: relative;
}
.image h2 {
  position: absolute;
  top: 18px;
  left: 27px;
  width: 100%;
  font-size: 40px;
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
  font-size: 14px;
  white-space: nowrap;
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
  font-size: 18px;
}
.phone-icon {
  margin-top: 5px;
}
</style>