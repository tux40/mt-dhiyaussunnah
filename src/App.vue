<template>
    <div id="app">
      <Header></Header>
      <Konten></Konten> 
      <Main></Main> 
    </div>
</template>

<script>
  import Header from "./components/Header" 
  import Konten from "./components/Konten"
  import Main from "./components/Main"
  export default {
      components: { Header, Konten, Main },
      } 
</script>


<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
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
} */
</style>
