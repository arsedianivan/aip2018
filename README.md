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

### Key principles of code style and design
Follow coding styles and recommendations on [Vuejs.org](https://vuejs.org):
- Use camelCase naming for components
- Use complete and understandable naming rather than abbreviations
- Use separate lines for array and object elements
- Use single quotes within Vue components
- Use double quotes within html
- Use hyphen for event names
- Use tab indentation of 2 spaces as code layer goes down
- Insert space after colons and before and after curly braces & equal signs
- Follow other standard W3C conventions within html, css, etc.
- Create separate folders to save and classify resources such as images and components
- Comment appropriately and where alternative solutions can be applied

Design of the application
- Use Vue components to separate functions
- Break the application down to lowest functional levels, each corresponding to one component
- Seperate persistence, logic and presentation layers
- Use in-component style which is easier to maintain and track
- Keep the application structure built with Vue CLI
- Create separate folders to save and classify resources such as images and components