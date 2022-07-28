<script>
export default {
  data() {
    return {
      
    }
  }
}


</script>

<template>
  <div class="wrapper">
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </div> 
</template>

<style scoped>

.wrapper {
  padding: 5px;
  width: 100%;
}

nav {
  display: flex;
  flex-direction: row;
  justify-content: center;
}



nav a {
  padding: 10px;
  color: hsla(160, 100%, 37%, 1);
}

nav a:hover {
  color: #181818;
  background: hsla(160, 100%, 37%, 1);
  padding: 10px;
}

</style>