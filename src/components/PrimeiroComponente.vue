<template>
    <div>
      <h1>olá vue</h1>
      <h5>meu nome é {{name}}</h5>
    </div>
  </template>
  
  <script>
  export default {
    name: 'PrimeiroComponente',
    data(){
      return {
        name:"Jefferson"
      }
    }
  }
  </script>