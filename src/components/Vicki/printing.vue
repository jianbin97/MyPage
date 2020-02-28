<template>
    <div>
      <navbar></navbar>
      <Web2></Web2>
      <py></py>
      <jv></jv>
      <imgHeader></imgHeader>
      <next2></next2>
      <prev></prev>
      <page></page>
      
    </div>
</template>

<script>
import navbar from './navbar.vue'
import Web2 from './Web2.vue'
import pythonPrinting from './pythonPrinting.vue'
import javaPrinting from './javaPrinting.vue'
import imgHeader from './imgHeader.vue'
import next2 from './next2.vue'
import page from './Page.vue'
import prev from './prev.vue'


export default {
  components: {
    'navbar': navbar,
    Web2,
    'py': pythonPrinting,
    'jv': javaPrinting,
    imgHeader,
    next2,
    page,
    prev,
    
    
  }
}
</script>

<style scoped>
div {
  width:1440px;
  height:200px;
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