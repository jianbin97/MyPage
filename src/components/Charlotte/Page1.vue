<template>
    <div>
      <Menu></Menu>
      <Header></Header>
      <Login></Login>
  
    </div>
</template>

<script>
import Menu from '../About/Header.vue'
import Header from './Page1/Header.vue'
import Login from './Page1/Login.vue'

export default {
  components: {
    Menu,
    Header,
    Login
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