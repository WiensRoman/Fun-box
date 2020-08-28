<template>
  <div class="card">
    <span>Сказочное заморское явство</span>
    <span>Нямушка</span>
    <span>с фуа-гра</span>
    <div class="cat"><label></label></div>
    <div class="oval"><span>0,5</span></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.card {
  position: absolute;
  width: 320px;
  height: 509px;
  left: 80px;
  top: 104px;
  background-color: white;
}
span:nth-of-type(1) {
  position: absolute;
  height: 19px;
  left: 15.94%;
  right: 20%;
  top: calc(50% - 19px / 2 - 224px);

  font-family: Trebuchet MS;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  /* identical to box height */

  color: #666666;
}
span:nth-of-type(2) {
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
span:nth-of-type(3) {
  position: absolute;
  height: 28px;
  left: 15.94%;
  right: 49.06%;
  top: calc(50% - 28px / 2 - 140.5px);

  font-family: Trebuchet MS;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #000000;
}
.cat {
position: absolute;
left: -7.5%;
right: -7.5%;
top: 40.86%;
bottom: -11.59%;
background-color: white;
}
label {
position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

background: url("../assets/Photo.png");
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
.oval span {
position: absolute;
height: 52px;
top: calc(50% - 13px);

font-family: Trebuchet MS;
font-style: normal;
font-weight: normal;
font-size: 42px;
line-height: 22px;
/* or 52% */

text-align: center;

color: #FFFFFF;
}
</style>