<template>
  <div class="home">
    <LoginCard></LoginCard>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import LoginCard from '../components/LoginCard.vue'
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    LoginCard
    // HelloWorld
  }
}
</script>
