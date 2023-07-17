<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>
  
  <script>
  export default {
    data () {
      return {
        title: "Clicky-T",
      }
    },
    methods:{
    }
  }
  </script>
  
  <style scoped>
    header{
        background:lightsalmon;
        padding: 10px;
    }
    h1{
        color: black;
        text-align: center;
    }
  </style>