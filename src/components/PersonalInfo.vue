<template>
  <div class="personalInfo">
    <h1>Hi {{ fullName }}</h1>
    <h2>Your Personal Info will be shown here</h2>
    <h3>People you may be interested in:</h3>
  </div>
</template>

<script>
export default {
  name: 'PersonalInfo',
  props: {
    fullName: String
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
