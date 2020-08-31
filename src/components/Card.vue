<template>
  <div class="card">
    <div class="border"></div>
    <div class="path-1"></div>
    <div class="path-2"></div>
    <div class="back">
    <span>Сказочное заморское явство</span>
    <span>Нямушка</span>
    <span>с фуа-гра</span>
    <span>10 порций мышь в подарок</span>
    <div class="cat"><div class="image"></div></div>
    <div class="oval">
      <span>0 5</span>
      <span>, кг</span>
    </div>
  </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.border{
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
  border: 4px solid #1698D9;
}

.card {
  position: absolute;
  width: 320px;
  height: 509px;
  left: 80px;
  top: 104px;
  background-image: url("../assets/background.png");
  border-radius: 17px;
  box-sizing: border-box;
  overflow: hidden;
  
  
}


.path-1{
width:115px;
height: 115px;
position: absolute;
left: -24.69%;
right: 85.8%;
top: -12.77%;
bottom: 88.32%;
border: 4px solid #1698D9;
box-sizing: border-box;
transform: rotate(45deg);
z-index: 120;

}
.path-2{
width:115px;
height: 115px;
position: absolute;
left: -24.69%;
right: 85.8%;
top: -12.77%;
bottom: 88.32%;
border: 4px solid black;
box-sizing: border-box;
transform: rotate(45deg) translate(-4px);
z-index: 120;
}

.back span:nth-child(1) {
  position: absolute;
  height: 19px;
  left: 15.94%;
  top: calc(50% - 19px / 2 - 224px);
  font-family: Trebuchet MS;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  /* identical to box height */

  color: #666666;
}
.back span:nth-child(2) {
  position: absolute;
  height: 56px;
  left: 15%;
  right: 19.06%;
  top: calc(50% - 56px / 2 - 181.5px);

  font-family: Trebuchet MS;
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
  top: calc(50% - 28px / 2 - 140.5px);

  font-family: Trebuchet MS;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #000000;
}

.back span:nth-child(4){
  position: absolute;
  top:28%;
  left:15.94%;
  font-family:Trebuchet MS;
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
}

.image {
position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;
background: url("../assets/Photo.png") no-repeat;

}
.oval {
position: absolute;
left: 70%;
right: 5%;
top: 75.44%;
bottom: 8.84%;
border-radius: 100%;
background: #1698D9;
}
.oval span:nth-child(1) {
position: absolute;
height: 22px;
left: 14%;
top: calc(50% - 15px);

font-family: "Trebuchet MS";
font-style: normal;
font-weight: normal;
font-size: 42px;
line-height: 22px;
/* identical to box height, or 52% */

text-align: center;

color: #FFFFFF;
}
.oval span:nth-child(2) {
position: absolute;
height: 52px;
top: calc(50% - 13px);

font-family: "Trebuchet MS";
font-style: normal;
font-weight: normal;
font-size: 42px;
line-height: 52%;
/* or 52% */

text-align: center;

color: #FFFFFF;
}
.back{
position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 5.7%;
background: #F2F2F2;
box-sizing: border-box;

z-index: 20px;

}





</style>