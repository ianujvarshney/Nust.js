<template>
  <div class="text-center">
    <h1>{{ title }}</h1>
    <ul>
      <li v-for="user in users">{{ user.name }}</li>
    </ul>
  </div>
</template>
<script setup lang="js">
export default{
  data(){
    return{
        title:"Users Access Data",
        users: []
      }
  },created(){
        fetch("https://jsonplaceholder.typicode.com/users")
        .then(response => response.json())
        .then(json => {this.users = json;});
    }
}
</script>
<style scoped>
h1 {
  background-color: blueviolet;
  color: white;
}
h1:hover {
  color: black;
}
</style>
