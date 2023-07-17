<template>
    <div >
      <footer>
        <p>{{copyright}}</p>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    data () {
      return {
      copyright: "Copyright 2023 Clicky-T"
      }
    },
    methods:{
    }
  }
  </script>
  
  <style scoped>
    footer{
      background:#3a3a3a;
      padding: 2px;
    }
    p{
      color: aquamarine;
      text-align: center;
    }

  </style>