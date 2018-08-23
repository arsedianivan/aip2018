<template>
  <div class="findSomeone">
    <img alt="Vue logo" src="../assets/logo.png">
    <button v-on:click="liked = !liked">{{liked? "like her":"Dislike her"}}</button>
  </div>
</template>

<script>
export default {
  name: 'FindSomeone',
  // props: {
  //   fullName: String
  // }
  data: function() {
    return {
      liked: true
    }
  }
}
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
