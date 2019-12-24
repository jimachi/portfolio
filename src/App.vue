<template>
  <div id="app">
    <myHeader></myHeader>
    <profile></profile>
    <skill></skill>
    <router-view/>
  </div>
</template>

<script>
import myHeader from "./components/myheader";
import profile from "./components/profile";
import skill from "./components/skill"

export default {
  name: 'App',
  components: {
    myHeader,
    profile,
    skill
  }
}
</script>

<style>
header {
  width: 100%;
  height: 10%;
}
</style>
