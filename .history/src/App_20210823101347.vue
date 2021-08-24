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
</style>
