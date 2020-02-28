<template>
    <router-link to="/syntax" id="prev"><button class="start">Prev  &#171;</button></router-link>
</template>

<script>
  export default {
    name: 'Users',
  }
</script> 

<style>
    .start {
        background-color: black;
        color: white;
        padding: 2px;
        font-size: 16px;
        border: none;
        border-radius:20px;
        cursor: pointer;
        font-family: Futura HV BT;
        font-style: normal;
        font-weight: 900px;
        font-size: 25px;
        position: absolute;
        width: 200px;
        height: 53px;
        left: 150px;
        top: 1050px;
        display: inline-block;
         
    }
    #prev {
      color:white;
    }
    

</style>