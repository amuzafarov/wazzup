<template>
  <div id="app">
    <Button />
  </div>
</template>

<script>
import Button from './components/Button';
export default {
  name: 'App',
  components: {
    Button
  }
}
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
