<template>
  <v-app>
    <v-content>
      <div id="app">
        <NavBar/>
      </div>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import NavBar from './components/NavBar';
export default {
  name: 'App',
  components: {
    NavBar
  },
  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
#app {
  font-family: "Raleway", sans-serif;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.input {
  background-color: white;
  opacity: 0.7;
  border: 1px solid #2c3e50;
  padding: 10px;
  margin-bottom: 20px;
}
.btn {
  background-color: #2c3e50;
  color: white;
  padding: 10px;
}
.test1{
  width:100%;
  background-color: red;
}
</style>
