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
  /* background: rgb(34, 193, 195); */
  /* background: linear-gradient(120deg, rgba(34, 193, 195, 1) 0%, rgba(253, 187, 45, 1) 100%); */
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

/* .sounds {
  position:initial;
  left: 50px;
  top: 150px;
} */
</style>
