<template>
  <div id="app">
    <!-- <div id="nav">
    </div> -->
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

html {
  height: 100%;
  background: #eecda3; /* fallback for old browsers */
  background: -webkit-linear-gradient(to top, #ef629f, #eecda3); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to top,
    #ef629f,
    #eecda3
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

body {
  max-height: 100%;
  margin: 0 auto;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

audio {
  width: 500px;
  height: 30px;
  margin: auto;
}
</style>
