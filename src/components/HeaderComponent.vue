<template>
  <header>
    <nav>
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/rules" class="nav-link">Rules</router-link>
      <router-link to="/timer" class="nav-link">Timer</router-link>
      <router-link to="/question" class="nav-link">Question</router-link>
      
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
}
</script>


<style scoped>
header {
  background-color: transparent;
  color: white;
  padding: 1rem;
  position: absolute;
  width: 100%;
  top: 0;
  transition: background-color 0.3s ease;
  z-index: 1000; 
}

.nav-link {
  text-decoration: none;
  margin: 0 0.5rem;
  color: white;
  transition: background-color 0.3s ease, color 0.3s ease;
  padding: 0.5rem 1rem;
  pointer-events: auto; 
}

.nav-link:hover, .router-link-exact-active {
  background-color: white;
  color: black;
  border-radius: 5px; 
}


.router-link-exact-active {
  font-weight: bold;
}
@media screen and (max-width: 480px) {
  header {
    width: max-content;
  }
}


</style>


  