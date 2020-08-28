<template>
  <div class="home">
    <div class="page">
      <span>Ты сегодня покормил кота?</span>
      <card>
        
      </card>
    </div>
  </div>
</template>

<script>
import Card from "@/components/Card.vue"
export default {
  name: "Home",
  components: {
    Card 
  }
};
</script>

<style scoped>
@font-face {
  font-family: "Exo2.0";
  src: url("../assets/fonts/Exo2.0-Thin.otf");
}
.home {
position: relative;
width: 1280px;
height: 680px;
background-color: #FFFFFF;
}
.page {
position: absolute;
width: 1280px;
height: 680px;
left: 0px;
top: 0px;
background-image: url("../assets/background.png");
}
span {
position: absolute;
width: 1120px;
height: 43px;
left: 80px;
top: 36px;
font-family: "Exo2.0";
font-style: normal;
font-weight: 250;
font-size: 36px;
line-height: 43px;
text-align: center;
color: #FFFFFF;
text-shadow: 0px 1px 1px #000000;
}
</style>>