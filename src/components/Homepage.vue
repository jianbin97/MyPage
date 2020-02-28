<template>
    <div id='homepage'>
      <Header></Header>
      <Body></Body>
      <Bottom></Bottom>
      <Footer></Footer>
    </div>
</template>

<script>
import Header from './Homepage/Header.vue'
import Body from './Homepage/Body.vue'
import Bottom from './Homepage/Bottom.vue'
import Footer from './Footer.vue'

export default {
  components: {
    Header,
    Body,
    Bottom,
    Footer
  }
}
</script>

<style scoped>
    #homepage{
      width:auto;
      height:100;
    }

    #footer {
  position: fixed;
  width: 454px;
  height: 30px;
  left: 1219px;
  bottom:10%;

  font-family: Futura Hv BT;
  font-style: normal;
  font-weight: 900;
  font-size: 14px;
  line-height: 17px;
  display: flex;
  align-items: center;

  color: #000000;
}

</style>