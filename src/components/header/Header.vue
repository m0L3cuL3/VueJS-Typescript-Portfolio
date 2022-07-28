
<!-- Script -->
<script lang="ts">

export default {
  data() {
    return {
      author: 'John Doe',
      description: 'A very passionate web developer!'
    }
  }
}

</script>

<!-- Template -->
<template>
    <header>
        <img src="../../assets/logo.svg" alt=""/>
        <h1 class="author">Hello, I'm {{ author }}!</h1>
        <p class="desc">{{ description }}</p>
    </header>
</template>

<!-- Styles -->
<style scoped>

header {
    display: flex;
    flex-direction: column;
    align-items: center;
}

img {
    padding: 16px;
    width: 100px;
    height: 100px;
} 

</style>