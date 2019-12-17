<template>
  <div>
    <header>
      <h1>Portfolio</h1>
    </header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link class="text-white px-3" to="/">home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="text-white px-3" to="/test1">test1</router-link>
          </li>
          <li class="nav-item">
            <router-link class="text-white px-3" to="/test2">test2</router-link>
          </li>
          <li class="nav-item">
            <router-link class="text-white px-3" to="/test3">test3</router-link>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style scoped>
  header {
    position: relative;
    height: 50vh;
    background: url("../assets/headerImg.jpg") center / cover;
  }

  h1 {
    color: white;
    text-align: center;
    line-height: 50vh;
  }
</style>