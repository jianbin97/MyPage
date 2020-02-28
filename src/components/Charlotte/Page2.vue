<template>
    <div>
        <Menu></Menu>
        <Info></Info>
      <Race></Race>  
    </div>
</template>

<script>
import Race from './Page2/Race.vue'
import Menu from '../About/Header.vue'
import Info from './Page2/Info.vue'

export default {
  components: {
    Race,
    Menu, 
    Info
  }
}
</script>

<style scoped>
div {
  height:auto;
  width:auto;
}
/* div {
  padding: 0px;
  margin: 0px;
  width: 1440px;
  height: 1024px;
  background-color: white;
}

html, body {
  padding: 0px;
  margin: 0px
} */


</style>