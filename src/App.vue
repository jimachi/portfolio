<template>
  <div id="app">
    <myHeader></myHeader>
    <profile></profile>
    <router-view/>
  </div>
</template>

<script>
import myHeader from "./components/myheader";
import profile from "./components/profile";

export default {
  name: 'App',
  components: {
    myHeader,
    profile
  }
}
</script>

<style>
header {
  width: 100%;
  height: 10%;
}
</style>
