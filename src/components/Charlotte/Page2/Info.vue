<template>
  <div class="head">
   
      <div id = "lang"> {{lang}} </div>
      <div id = "diff"> {{diff}} </div>
        

      <div> <router-link to="/Page3" id = "ex1">  Exercise 1 </router-link>
      </div>

      <div> <router-link to="/Page3" id = "ex2">  Exercise 2 </router-link>
      </div>

      <div> <router-link to="/Page3" id = "ex3">  Exercise 3 </router-link>
      </div>

      <div> <router-link to="/Page3" id = "ex4">  Exercise 4 </router-link>
      </div>

      <div> <router-link to="/Page3" id = "ex5">  Exercise 5 </router-link>
      </div>
 
  </div>
</template>


<script>
export default {
  
  data(){
    return{
      lang: 'Language:',
      diff: 'Difficulty:',
      ex1: 'Exercise 1',
      ex2: 'Exercise 2',
      ex3: 'Exercise 3',
      ex4: 'Exercise 4',
      ex5: 'Exercise 5'
    
        }
  }
}
</script>


<style scoped>

#lang {
    position: absolute;
    width: 700px;
    height: 115px;
    left: 215px;
    top: 100px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 80;
    font-size: 25px;
    line-height: 36px;
    display: flex;
    align-items: left;
    text-align: left;
        
}

#diff{
    position: absolute;
    width: 700px;
    height: 115px;
    left: 800px;
    top: 100px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 80;
    font-size: 25px;
    line-height: 36px;
    display: flex;
    align-items: left;
    text-align: left;
        
}


#ex1 {
    position: absolute;
    width: 146px;
    height: 50px;
    left: 520px;
    top: 370px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 36px;
}

#ex2 {
    position: absolute;
    width: 146px;
    height: 50px;
    left: 950px;
    top: 370px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 36px;

}

#ex3 {
  position: absolute;
    width: 146px;
    height: 50px;
    left: 1270px;
    top: 500px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 36px;
}

#ex4 {
    position: absolute;
    width: 146px;
    height: 50px;
    left: 950px;
    top: 670px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 36px;

}

#ex5 {
    position: absolute;
    width: 146px;
    height: 50px;
    left: 520px;
    top: 670px;

    font-family: Futura Hv BT;
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 36px;

}





</style>