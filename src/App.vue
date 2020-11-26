<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" name="" id="" class="search-bar" placeholder="Search...">
      </div>
    </main>
  </div>
</template>

<script>

const API_KEY = process.env.VUE_APP_API_KEY;

export default {
  name: 'App',
  data(){
    return {
      api_key: API_KEY
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
  background-image: url('./assets/cold-bg.jpg')
}

</style>
