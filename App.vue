<template>  
    <div>  
      <label for="name">Votre nom :</label>  
      <input v-model="name" id="name" type="text" />  
      <p>Bonjour, {{ name }} ! 👋</p>  
    </div>  
  </template>  
  
  <script>  
  export default {  
    data() {  
      return {  
        name: ''  
      };  
    }  
  };  
  </script>  
  