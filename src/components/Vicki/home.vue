<template>
    <div>
      <navbar></navbar>
      <btn></btn>
      <select2></select2>
      <select3></select3>
      <imgHeader></imgHeader>
      <subWeb></subWeb>
      <Web1></Web1>
      
    </div>
</template>
 
<script>
import navbar from './navbar.vue'
import btn from './btn.vue'
import select2 from './select2.vue'
import select3 from './select3.vue'
import imgHeader from './imgHeader.vue'
import subWeb from './subWeb.vue'
import Web1 from './Web1.vue'
 
 
 
export default {
  components: {
    'navbar': navbar,
    btn,
    imgHeader,
    select2,
    select3,
    subWeb,
    Web1
    
    
    
  }
}
</script>
 
<style>
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
