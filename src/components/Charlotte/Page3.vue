<template>
    <div>
        <Menu></Menu>
        <Question></Question>
    </div>
</template>

<script>
import Question from './Page3/Question.vue'
import Menu from '../About/Header.vue'


export default {
  components: {
    Question,
    Menu
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