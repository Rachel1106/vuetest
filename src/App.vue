<template>
  <div id="app">
    <Asides></Asides>
    <Right></Right>
  </div>
</template>

<script>
import Asides from "@/components/aside/aside"
import Right from '@/components/right/index'
export default {
  components:{
    Asides,
    Right
  }
}
</script>

<style>
  #app{
    width:100%;
    display:flex;
    justify-content:space-between;
  }
  .aside{
    width:200px;
  }
  .right{
    flex:1;
    margin-left:10px;
  }
</style>
