<template>
  <Menu />
  <Main />

</template>

<script>
  import Main from './components/Main.vue';
  import Menu from './components/Menu.vue';
  

  export default{
    name:  'App',
    components: {
      Main,
      Menu
    }
  }
</script>