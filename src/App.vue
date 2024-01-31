<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'HelloWorld',
  components: {
    AppHeader,
    AppMain
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
</template>

<style>
h1 {
  text-decoration: underline;
}
</style>