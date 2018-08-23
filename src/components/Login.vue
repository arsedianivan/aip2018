<template>
  <div v-if="!isLoggedIn" class="login">
    <div class="loginBox">
      User name<br>
      <input type="text" name="username"><br>
      Password<br>
      <input type="password" name="password"><br>
      <!-- <button v-on:click="isLoggedIn = !isLoggedIn">Login</button><br> -->
      <button v-on:click="isLoggedIn = !isLoggedIn">Login</button><br>
      <input type="button" value="Sign up">
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
  // props: {
  //   isLoggedIn: false
  // }
  data: function() {
    return {
      isLoggedIn: false
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
