<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search...">
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      api_key:'9a1ed7d1efa5000413ec6fc31687ab4c',
    }
  }
}
</script>
 
<style>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
body{
  font-family: 'montserrat', sans-serif;
}
#app{
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}
main{
  min-height: 100vh;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0,75))
}
</style>
