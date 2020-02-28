<template>
    <div>
      <navbar></navbar>
      <Web></Web>
      <ps></ps>
      <js></js>
      <imgHeader></imgHeader>
      <next></next>
      <Page></Page>
      
    </div>
</template>

<script>
import navbar from './navbar.vue'
import Web from './Web.vue'
import pythonSyntax from './pythonSyntax.vue'
import javaSyntax from './javaSyntax.vue'
import imgHeader from './imgHeader.vue'
import next from './next.vue'
import Page from './Page.vue'

export default {
  components: {
    'navbar': navbar,
    Web,
    'ps': pythonSyntax,
    'js': javaSyntax,
    imgHeader,
    next,
    Page
    
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