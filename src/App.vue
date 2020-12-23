<template>
    <the-header title="RememberMe"></the-header>
    <the-resources></the-resources>
</template>

<script>
import TheHeader from "./components/layout/TheHeader.vue";
import TheResources from "./components/resources/TheResources.vue";

export default {
    components:{
        TheHeader,
        TheResources
    }
}
</script>

<style>
/* new amazing font */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'open-sans', sans-serif;
}

body {
  margin: 0;
}
</style>