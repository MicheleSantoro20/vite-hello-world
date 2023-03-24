<script>
  import AppTitle from './components/AppTitle.vue';
  import jumbotron from './components/jumbotron.vue';

  export default{

    components: {
      AppTitle,
      jumbotron
    }

  }
</script>

<template>

  <AppTitle/>
  <jumbotron />
</template>

<style>
body {
  background-color: pink;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
