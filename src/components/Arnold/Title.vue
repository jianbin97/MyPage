<template>
  <div class="text">
    <div id='img'></div>
    <span id='text1'>{{text1}}</span>
  </div>
</template>

<script>
export default {
  data() {
      return {
          text1: 'Programming Languages',
          image: '/assets/title1.jpg'
      }
  }
}
</script>

<style scoped>
#img {
    position: absolute;
    width: 100%;
    height: 20%;
    left: 0px;
    top: 7%;
     background: url('/assets/title1.jpg'); 
    background-size: cover;
}

#text1 {
    position: absolute;
    width: 609px;
    height: 87px;
    left: 70%;
    top: 90px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 900;
    font-size: 30px;
    line-height: 36px;
    display: flex;
    align-items: center;
    text-align: center;

    color: #000000;
}
</style>

