<template>
  <div class="home">
    <div class="page">
      <span>Ты сегодня покормил кота?</span>
      <card> </card>
      <card2> </card2>
      <card3> </card3>
    </div>
  </div>
</template>

<script>
import Card from "@/components/Card.vue";
import Card2 from "@/components/Card2.vue";
import Card3 from "@/components/Card3.vue";
export default {
  name: "Home",
  components: {
    Card,
    Card2,
    Card3
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
  width: 100%;
  height: 100%;
}
.page {
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0px;
  top: 0px;
}
span {
  display: flex;
  flex-direction: row;
  justify-content: center;
  font-family: "Exo2.0";
  font-style: normal;
  font-weight: 250;
  font-size: 36px;
  line-height: 43px;
  text-align: center;
  color: #ffffff;
  text-shadow: 0px 1px 1px #000000;
}
.cards {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
</style>
