<template>
  <div id="app">
    <myheader></myheader>
    <router-view/>
    <b-button>Button</b-button>
  </div>
</template>

<script>
import myheader from './components/myheader'

export default {
  name: 'App',
  components: {
    myheader
  }
}
</script>

<style>
body {

}

header {
  width: 100%;
  height: 10%;
}
</style>
