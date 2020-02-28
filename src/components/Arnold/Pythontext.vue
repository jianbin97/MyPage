<template>
  <div class="text">
    <img src="/assets/python.png">
    <span id='text1'>Python is a general-purpose, versatile and modern programming language.</span>
    <router-link to="/python" id='text2'>Let's Go</router-link>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
#text1 {
    position: absolute;
    width: 346px;
    height: 96px;
    left: 132px;
    top: 620px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 900;
    font-size: 20px;
    line-height: 24px;

    color: #000000; 
}

#text2 {
    position: absolute;
    width: 125px;
    height: 30px;
    left: 242px;
    top: 730px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 900;
    font-size: 20px;
    line-height: 24px;
    text-decoration-line: underline;

    color: #000000;
}

img {
  position: absolute;
  width: 460px;
  height: 153px;
  left: 5%;
  top: 350px;
}

</style>
