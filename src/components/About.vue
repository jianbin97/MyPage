<template>
    <div id='about'>
        <about-header></about-header>
        <Title></Title>
        <Body></Body>
        <Footer id=footer></Footer>
    </div>
</template>

<script>
import Header from './About/Header.vue'
import Body from './About/Body.vue'
import Title from './About/Title.vue'
import Footer from './Footer.vue'

export default {
  components: {
    'about-header':Header,
    Body,
    Title,
    Footer
  }
}
</script>

<style scoped>
    #about{
        width:100%;
        height: auto;
        margin:auto;
        overflow:hidden;
    }

    #footer {
        position: absolute;
        width: 454px;
        height: 30px;
        left: 1219px;
        top: 1350px;

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