<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Login v-if="!isLoggedIn" v-on:logged-in="isLoggedIn = !isLoggedIn"/>
    <PersonalInfo fullName="Steve"/>
    <FindSomeone/>
    <Calendar/>
    <Footer/>
  </div>
</template>

<script>
import Login from './components/Login.vue'
import PersonalInfo from './components/PersonalInfo.vue'
import Calendar from './components/Calendar.vue'
import Footer from './components/Footer.vue'
import FindSomeone from './components/FindSomeone.vue'

export default {
  name: 'app',
  components: {
    Login,
    PersonalInfo,
    FindSomeone,
    Calendar,
    Footer
  },
  data: function () {
    return {
      isLoggedIn: false
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
