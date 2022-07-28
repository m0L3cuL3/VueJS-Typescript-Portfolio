<script setup lang="ts">
import TitlePage from "../components/home_components/TitlePage.vue"

const title = 'Home'

</script>

<template>
    <div class="container">
      <TitlePage :page_title="title"/>
    </div>
</template>

<style scoped>
    .container {
        padding: 32px;
    }
</style>
