<template>
  <div class="error"> 
    <h1>{{ msg }}</h1>
  </div>
</template>


<script>
      export default {
        name: 'Error',
        data () {
          return {
            msg: '访问失败，重新访问'
          }
        }
      }
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
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