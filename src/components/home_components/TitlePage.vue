<script lang="ts">

export default {
    props: {
        page_title: String
    }
}

</script>

<template>
    <div class="title-container">
        <h1 class="page-title-heading">{{ page_title }}</h1>
    </div>
</template>

<style scoped>
.page-title-heading {
	-webkit-animation: page-title-heading 1s cubic-bezier(0.215, 0.610, 0.355, 1.000) both;
	        animation: page-title-heading 1s cubic-bezier(0.215, 0.610, 0.355, 1.000) both;
}

@-webkit-keyframes page-title-heading {
  0% {
    letter-spacing: 1em;
    -webkit-transform: translateZ(400px) translateY(-300px);
            transform: translateZ(400px) translateY(-300px);
    opacity: 0;
  }
  40% {
    opacity: 0.6;
  }
  100% {
    -webkit-transform: translateZ(0) translateY(0);
            transform: translateZ(0) translateY(0);
    opacity: 1;
  }
}
@keyframes page-title-heading {
  0% {
    letter-spacing: 1em;
    -webkit-transform: translateZ(400px) translateY(-300px);
            transform: translateZ(400px) translateY(-300px);
    opacity: 0;
  }
  40% {
    opacity: 0.6;
  }
  100% {
    -webkit-transform: translateZ(0) translateY(0);
            transform: translateZ(0) translateY(0);
    opacity: 1;
  }
}

</style>