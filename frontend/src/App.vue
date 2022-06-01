<template>
  <div id="nav">
    <h1> {{this.msg}} </h1>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    <button @click="SetMessage"> Set message</button>
  </div>
  <!-- <router-view/> -->
</template>

<script>

export default {
  data() {
    return {
      msg:  '0',
    }
  },
  methods : {
    SetMessage: function() {
      this.msg = 'yo';
    }
  }
}
</script>

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
</style>
