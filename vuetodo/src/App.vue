<template>
  <div id="app">
    <h2>What do I do today ?</h2>
    <div class="hometask">
      <div v-for="task in tasks" v-bind:key="task.id" class="tugas">
          <p>{{task.name}}</p>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: 'App',
  data: function (){
   return { tasks : [
      {
        id: 1,
        name:'Cleaning Bed Room'
      },
      {
        id: 2,
        name:'Wash Dishes'
      },
      {
        id: 3,
        name:'Motorbike Service'
      },
    ]
  }
  },
  components: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
