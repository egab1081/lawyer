<template>
  <div class="footer-left">
    <div class="left-left">
      <div class="image">
        <img src="~/assets/curcle.png" alt />
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
        <img src="~/assets/locate.png" alt />
      </div>
      <div>
        <h2>Адрес компании:</h2>
        <span>г.Пермь, ул.</span>
        <br />
        <span>Екатерининская 120а</span>
      </div>
    </div>
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
      <a href>Заказать звонок</a>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
.footer-left {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
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
.left-left {
  display: flex;
  flex-direction: row;
  align-items: center;
}
.left-left h1 {
  font-size: 18px;
  font-weight: normal;
}
.left-right {
  display: flex;
  flex-direction: row;
  align-items: center;
}
.left-right span {
  font-size: 18.5px;
  white-space: nowrap;
}
.left-right h2 {
  text-decoration: underline;
  font-weight: normal;
}
.right-left {
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
a {
  padding: 30px 90px;
  background-color: #dadada;
  border-radius: 10px;
  color: #000;
  text-decoration: none;
  font-size: 18px;
}
</style>