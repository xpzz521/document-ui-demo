<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to the Document UI Demo
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1 {
  color: #42b983;
}
</style>