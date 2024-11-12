<!-- <template>
    <div id="nav">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/Jogos">Jogos</RouterLink>
    <RouterLink to="/Times">Times</RouterLink>
    <RouterLink to="/Campeonatos">Campeonatos</RouterLink>
    


</div>

</template>

<script>

</script>

<style scoped>
#nav{
    background-color: white;
    height: 75px; 
    /* justify-content: flex-end;
    align-items: center; */
} 

#nav a{
    color: black;
    margin: 12px;
}

</style> -->
<template>
    <nav class="navbar">
      <ul class="navbar-menu">
        <li><router-link to="/" class="navbar-link">Home</router-link></li>
        <li><router-link to="/Jogos" class="navbar-link">Jogos</router-link></li>
        <li><router-link to="/times" class="navbar-link">Times</router-link></li>
        <li><router-link to="/campeonatos" class="navbar-link">Campeonatos</router-link></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
  .navbar {
    background-color: #ffffff;
    padding: 10px;
  }
  
  .navbar-menu {
    display: flex;
    justify-content: center;
    list-style: none;
    margin-left: -700px;
  }
  
  .navbar-menu li {
    margin: 6px;
  }
  
  .navbar-link {
    color: rgb(0, 0, 0);
    text-decoration: none;
    font-size: 18px;
    padding: 10px;
    transition: background-color 0.3s;
  }

  
  
  .navbar-link:hover {
    background-color: #555;
    border-radius: 5px;
  }
  </style>