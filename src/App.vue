<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Enter your City" />
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data () {
    return{
      apiKey: '653cb2ac019d0a5e7af7f1bcf283ca4c'
    }
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main{
  min-height: 100vh;
  padding: 25px;
}
</style>
