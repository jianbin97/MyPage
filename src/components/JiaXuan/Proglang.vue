<template>
<div id="page">
<navbar></navbar>
<div class="container">
    <app-header position: fixed></app-header>
    <section id="proglang">
            <h1> SEARCH MODULES </h1>
            <p></p>
            <div id = "searchmodules">
                <b>Module Subject Area: </b> 
                <input type="text" name="subjectarea" v-model="subjectarea" placeholder="e.g. BT, CS" 
                style="height:40px; width:300px; font-family: 'Futura Hv BT'; font-size: 20px"/>
                <a href="#Search">&#x1f50d;</a>
                <p></p>
                <b>Module Catalog No. : </b>
                <input type="text" name="catalognumber" v-model="catalognumber" placeholder="e.g. 1010, 1101" 
                style="height:40px; width:300px; font-family: 'Futura Hv BT'; font-size: 20px"/>
                <a href="#Search">&#x1f50d;</a>
            </div>
            <p> </p>
            
            <router-link id="link" to="/CS1010S" tag="btn"><button type="button" id="btn"
            style="background-color:#84CEEB; width:240px; height:50px
            font-family:'Futura Hv BT'; font-size:25px; color:#FFFFFF">Go</button></router-link> 
            
        </section>
    </div>
</div>
</template>

<script>
import navbar from '../About/Header.vue'
import Header from './Header.vue'
export default {
    components: {
        'navbar': navbar,
        'app-header': Header
    }
}
</script>

<style scoped>

    #page {
        width: 100%;
        height: 100%;
    }

    #proglang {
        width: 860px;
        height: 100%;
        /*background-color: lightgrey*/
    }

    #btn {
        font-family: 'Futura Hv BT'
    }

    #searchmodules {
        font-size: 30px;
    }

    /*#overlay {
        position: fixed; 
        display: on; 
        width: 17%; 
        height: 35%; 
        top: 50;
        left: 0;
        right: 0;
        bottom: 0;
        background-color:grey; 
        border-inline-color:black;
        z-index: 2; 
        cursor: pointer; 
    }*/

    .container {
        width:100%;
        height:100%;
        font-family: 'Futura Hv BT';
        text-align: center;
        color: rgb(63, 55, 55);
        padding-left: 300px;
        padding-right: 300px;
        padding-top: 200px;
    }

    h1 {
        font-family: 'Futura Hv BT';
        font-size: 40px;
        color: #000000;
        margin: 50px;
        background-color: #84CEEB;
    }

    p {
        margin: 40px;
    }

    a {
        margin: 20px;
        font-size: 34px;
    }

</style> 