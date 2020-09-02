<template>
  <div class="card2">
    <div
      class="border"
      @click="selected = !selected"
      :class="{ selectedBorder: selected }"
    ></div>
    <div class="path-1" :class="{ selectedPath1: selected }"></div>
    <div class="path-2"></div>
    <div class="back">
      <span>Сказочное заморское явство</span>
      <span>Нямушка</span>
      <span>с рыбой</span>
      <span>40 порций 2 мыши в подарок</span>
      <div class="cat"><div class="image"></div></div>
      <div class="oval" :class="{ selectedOval: selected }">
        <span>2</span>
        <span>кг</span>
      </div>
      <div class="footer" v-if="!selected">
        Чего сидишь? Порадуй котэ, <a @click="selected = !selected">купи.</a>
      </div>
      <div class="footer" v-else>
        Головы щучьи с чесночком да свежайшая сёмгушка
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      selected: false
    };
  }
};
</script>

<style scoped>
.border {
  position: absolute;
  width: 320px;
  height: 470px;
  left: 0px;
  top: 0px;
  background-image: url("../assets/background.png");
  border-radius: 17px;
  box-sizing: border-box;
  overflow: hidden;
  z-index: 110;
  background: transparent;
  border: 4px solid #1698d9;
}
.card2 {
  position: absolute;
  width: 320px;
  height: 509px;
  left: 40%;
  top: 104px;
  border-radius: 17px;
  box-sizing: border-box;
  overflow: hidden;
}
.border:hover {
  cursor: pointer;
  border: 5px dashed #1698d9;
}
.path-1 {
  width: 115px;
  height: 115px;
  position: absolute;
  left: -24.69%;
  right: 85.8%;
  top: -12.77%;
  bottom: 88.32%;
  border: 4px solid #1698d9;
  box-sizing: border-box;
  transform: rotate(45deg);
  z-index: 120;
}
.path-2 {
  width: 115px;
  height: 115px;
  position: absolute;
  left: -24.69%;
  right: 85.8%;
  top: -12.77%;
  bottom: 88.32%;
  background: url("../assets/background.png") no-repeat 2% 15%;
  box-sizing: border-box;
  transform: rotate(45deg) translate(-4px);
  z-index: 120;
}

.back span:nth-child(1) {
  position: absolute;
  height: 19px;
  left: 15.94%;
  top: 2%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  color: #666666;
}
.back span:nth-child(2) {
  position: absolute;
  height: 56px;
  left: 15%;
  right: 19.06%;
  top: 6%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 56px;
  color: #000000;
}
.back span:nth-child(3) {
  position: absolute;
  height: 28px;
  left: 15.94%;
  top: 17%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #000000;
}

.back span:nth-child(4) {
  position: absolute;
  top: 28%;
  left: 15.94%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  color: #666666;
}
.cat {
  position: absolute;
  left: -7.5%;
  right: -7.5%;
  top: 40.86%;
  bottom: -11.59%;
  max-height: 60%;
  border-radius: 10px;
}

.image {
  position: absolute;
  left: 0%;
  right: 0%;
  top: 0%;
  bottom: 0%;
  background: url("../assets/Photo.png") no-repeat;
  border-radius: 61px;
}
.oval {
  position: absolute;
  left: 70%;
  right: 5%;
  top: 75.44%;
  bottom: 8.84%;
  border-radius: 100%;
  background: #1698d9;
}
.oval span:nth-child(1) {
  position: absolute;
  height: 22px;
  left: 35%;
  top: 30%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: normal;
  font-size: 42px;
  line-height: 22px;
  text-align: center;
  color: #ffffff;
}
.oval span:nth-child(2) {
  position: absolute;
  height: 52px;
  top: 55px;
  left: 25%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: normal;
  font-size: 22px;
  line-height: 52%;
  text-align: center;
  color: #ffffff;
}
.back {
  position: absolute;
  width: 320px;
  height: 466px;
  left: 0px;
  top: 0px;
  background: #f2f2f2;
  box-sizing: border-box;
  border-radius: 5%;
  z-index: 20px;
}
.footer {
  position: absolute;
  height: 15px;
  left: 17.34%;
  right: 17.34%;
  top: 100%;
  font-family: "Trebuchet MS";
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 15px;
  margin-top: 4.5px;
  text-align: center;

  color: #ffffff;
}
a {
  color: rgb(112, 188, 250);
  border-bottom: 1px dashed rgb(112, 188, 250);
}
a:hover {
  color: rgb(44, 129, 199);
  cursor: pointer;
  border-bottom: 1px dashed rgb(44, 129, 199);
}
a:active {
  color: #d91667;
  border-bottom: 1px dashed #d91667;
}
.selectedBorder {
  position: absolute;
  width: 320px;
  height: 470px;
  left: 0px;
  top: 0px;
  background-image: url("../assets/background.png");
  border-radius: 17px;
  box-sizing: border-box;
  overflow: hidden;
  z-index: 110;
  background: transparent;
  border: 4px solid #d91667;
}

.selectedOval {
  position: absolute;
  left: 70%;
  right: 5%;
  top: 75.44%;
  bottom: 8.84%;
  border-radius: 100%;
  background: #d91667;
}
.selectedPath1 {
  width: 115px;
  height: 115px;
  position: absolute;
  left: -24.69%;
  right: 85.8%;
  top: -12.77%;
  bottom: 88.32%;
  border: 4px solid #d91667;
  box-sizing: border-box;
  transform: rotate(45deg);
  z-index: 120;
}
</style>
