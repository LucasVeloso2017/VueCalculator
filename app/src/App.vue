<template>
  <div id="app">
    <h1>Calculadora</h1>
    <calculator/>
  </div>
  

</template>



<script>
import calculator from './components/main/calculator'
export default {
  components:{ calculator}


}
</script>

<style>
  *{
    margin:0;
    font-family: "RobotoMono", monospace;
  }
  #app{
    
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #fff;
    background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));

  }


</style>
