<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <input type="text" v-model="msg">
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1{
        font-size: 20px;
        color: #42b983;
    }

</style>
