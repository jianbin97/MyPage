<template>
  <div class="container">
    <div id = "rect"> </div>

    <div id = "username">
      <b> Language </b>
      <input type="text" name="lang"
      v-model="lang"
      style="height:50px; width:300px; font-family: 'Futura Hv BT'; font-size: 25px"/>
      
     <p></p>

      <b> Difficulty </b>
      <input type="text" name="diff" 
      v-model="diff" 
      style="height:50px; width:300px; font-family: 'Futura Hv BT'; font-size: 25px"/>
      </div>

    <router-link to="/Page2" tag="race">
      <div id = "race">
        Go
      </div>
    </router-link>

  
    </div>
 
</template>

<script>
export default {
  
  data(){
    return{}

  },
  methods:{
    
  }
}
</script>


<style scoped>
  #rect {
    
    position: absolute;
    width: 690px;
    height: 353px;
    left: calc(50% - 690px/2 - 12px);
    top: calc(50% - 250px/2 + 0.5px);
    mix-blend-mode: normal;
    border: 1px solid #000000;
    box-sizing: border-box;
  }

  #username {
    font-size: 30px;
    position: absolute;
    width: 500px;
    height: 150px;
    left: 500px;
    top: 430px;
  }
  #race {

    position: absolute;
    width: 250px;
    height: 69px;
    left: 1093px;
    top: 700px;
    background-color:#84CEEB;
    font-family:'Futura Hv BT'; 
    font-size:25px;
    font-style: normal;
    font-weight: normal;
    text-align: center;
    padding: 14px 20px;
    margin: 8px 0;
    border: 1px solid #FFFFFF;
    box-sizing: border-box;

  }

 

</style>