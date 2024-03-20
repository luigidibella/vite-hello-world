<script>

export default {
  data(){
    return{
      title: 'Hello Vite',
      paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, officiis? '
    }
  }

}
 
</script>

<template>
  <div>
    <h1>{{ title }}</h1>

    <p>&nbsp; {{ paragraph }} &nbsp;</p>
    
  </div>
</template>

<style scoped>
  div:hover {
    background: black;
    background-size: none;
    animation: none;
  }
  
  h1 {
    color: white;
  }
  
  p {
    color: white;
}
</style>