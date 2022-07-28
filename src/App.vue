<script setup lang="ts">
import NavBarComponent from './components/nav/NavBar.vue'
import HeaderComponent from './components/header/Header.vue'
</script>

<template>

<!-- Header -->
<HeaderComponent/>

<!-- Navbar -->
<NavBarComponent/>

<!-- Contents -->
<RouterView />

</template>

<style scoped>

</style>
