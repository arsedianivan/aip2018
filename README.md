# aip2018

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Install MongoDb
```
Create a folder called data to store.
mkdir \data\db
```

### Run MongoDb
```
mongod
```

###Key principles of code style and design

###Removed unused codes
```
Bad
<script>

export default {
  name: 'Calendar',
  // props: {
  //   fullName: String
  // }
}

Good
<script>
export default {
  name: 'Calendar',
}
```

###Use specific styling and begin with prefix, such as Base, App, or V as suggested in Vuejs.org
```
Bad
VueCalender.vue

Good
BaseCalender
or
VCalender
```

###Have seperate files for style
```
Bad
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

Good

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

Stylesheet in a seperate File

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
```


