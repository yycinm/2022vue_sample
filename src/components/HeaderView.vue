<template>
  <header class="header">
    <h1><a href="#">logoddd</a></h1>
    <div class="nav">
        <ul>
                     
            <li v-for="item in menu" :key="item">{{item}}</li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {
data(){
    return {
        menu:["home","product","online","comunity"]
    }
}
}
</script>

<style>
.header{
  width: 1200px;margin: 0 auto;
  display: flex;}

  .nav{
    margin-left: auto;height: 40px;
  }
  .nav ul{
    display: flex;height: 100%;
  
  }
  li{
        display: flex;
    }


</style>