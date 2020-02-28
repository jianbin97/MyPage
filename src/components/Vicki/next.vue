<template>
    <router-link to="/printing" id="next"><button class="start">Next  &#187;</button></router-link>
    
</template>

<script>
  
  export default {
    name: 'Users',
  }
</script>

<style scoped>
    .start {
        background-color: black;
        color: white;
        padding: 2px;
        
        border: none;
        border-radius:20px;
        cursor: pointer;
        font-family: Futura HV BT;
        font-style: normal;
        font-weight: 900px;
        font-size: 26px;
        position: absolute;
        width: 200px;
        height: 53px;
        left: 1070px;
        top: 1050px;
        display: inline-block;
         
    }
    #next {
      color:white;
    }

   
</style>