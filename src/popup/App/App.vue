<template>
  <div class="main_app">
    <div class="d-flex">
      <h3>請輸入年齡(實歲)</h3>
      <input type="number" v-model="age" />
      <button>確定</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data: () => ({
    age: ''
  })
}
</script>

<style>
.main_app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
button {
  background-color: #1a70e5;
  color: #ffffff;
  margin-top: 10px;
  padding: 10px;
  border-radius: 5px;
  border: none;
}
</style>
