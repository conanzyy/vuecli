<template>
  <div id="app">
    <img src="./assets/logo.png">
    <ul>
      <li>
        <router-link to="/A">Go to A</router-link>
      </li>
      <li>
        <router-link to="/B">Go to B</router-link>
      </li>
    </ul>
    <router-view/>
    <input type="text" v-model="msg" v-show="true" v-focus/>
  </div>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      msg: '12124'
    }
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
