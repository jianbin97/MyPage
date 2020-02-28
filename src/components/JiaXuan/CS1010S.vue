<template>
<div id="page">
<navbar></navbar>
<div class="container">
    <app-header id="blueheader"></app-header>
    <div id="cs1010s">
            <h1><u>CS1010S</u></h1>

            <section id = "searchmodules">
                <b>Module Subject Area: </b> 
                <input type="text" name="subjectarea" v-model="subjectarea" placeholder="CS" 
                style="height:30px; width:300px; font-family: 'Futura Hv BT'; font-size: 17px"/>
                <a href="#Search">&#x1f50d;</a>
                <p></p>
                <b>Module Catalog No. : </b>
                <input type="text" name="catalognumber" v-model="catalognumber" placeholder="1010S" 
                style="height:30px; width:300px; font-family: 'Futura Hv BT'; font-size: 17px"/>
                <a href="#Search">&#x1f50d;</a>
            </section>

            <p></p>
            <button type="button" id="btn"
            style="background-color:#84CEEB; width:200px; height:50px
            font-family:'Futura Hv BT'; font-size:25px; color:#FFFFFF"> Go </button>

            <section id="modsynopsis1">
                <b>Module Synopsis: </b>
                <section id = "modsynopsis2">
                    This module introduces the fundamental concepts of problem solving by computing and programming using an 
                    imperative programming language. Topics covered include problem solving by computing, writing pseudo-codes, 
                    basic problem formulation and problem solving, program development, coding, testing and debugging, fundamental 
                    programming constructs (variables, types, expressions, assignments, functions, control structures, etc.), 
                    fundamental data structures: arrays, strings and structures, simple file processing, and basic recursion.
                </section>
            </section>

            <section id="relevlang1">
                <b>Relevant Languages: </b>
                <section id = "relevlang2">
                    Python
                </section>
            </section>

            <section id="recomex1">
                <b>Recommended Ex. : </b>
                <section id="recomex2">
                    <button type="py1" id="btn" name="langbutton" style="background-color:#lightgreen; width:120px; height:40px
                    font-family:'Futura Hv BT'; font-size:15px; color:#ffffff">Python 1</button>
                    <button type="py2" id="btn" name="langbutton" style="background-color:#green; width:120px; height:40px
                    font-family:'Futura Hv BT'; font-size:15px; color:#ffffff">Python 2</button>
                    <button type="py3" id="btn" name="langbutton" style="background-color:#green; width:120px; height:40px
                    font-family:'Futura Hv BT'; font-size:15px; color:#ffffff">Python 3</button>
                </section>
            </section>
            
    </div>
</div>
</div>
</template>

<script>
import navbar from './navbar.vue'
import Header from './Header.vue'
export default {
    components: {
        'navbar': navbar,
        'app-header': Header
    }
}
</script>

<style scoped>
.container {
    width:100%;
    height:100%;
    font-family: 'Futura Hv BT';
    text-align: center;
    color: #2c3e50;
    padding-left: 250px;
    padding-right: 250px;
}

#page {
    width: 100%;
    height: 100%;
}

#cs1010s {
    margin-top: 250px;
}

a {
    margin: 20px;
    font-size: 25px;
}

#btn {
    font-family: 'Futura Hv BT';
}

#langbutton {
    padding-right: 10px;
}

#searchmodules {
    margin-left: 85px;
    text-align: left;
}

#modsynopsis1 {
    padding-top: 50px;
    margin-left: 85px;
    text-align: left;
}

#modsynopsis2 {
    width: 600px;
    margin-left: 180px;
    text-align: left;
}

#relevlang1 {
    padding-top: 30px;
    margin-left: 85px;
    text-align: left;
}

#relevlang2 {
    margin-left: 180px;
    text-align: left;
}

#recomex1 {
    padding-top: 30px;
    margin-left: 85px;
    text-align: left;
}

#recomex2 {
    margin-left: 180px;
    text-align: left;
    design: inline;
}

</style>
