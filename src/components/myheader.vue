<template>
  <div>
    <header>
      <h1>Portfolio</h1>
    </header>
    <nav>
      <ul class="float">
        <li><a href="#">Profile</a></li>
        <li><a href="#">SKILL</a></li>
        <li><a href="#">WORKS</a></li>
        <li><a href="#">CONTACT</a></li>
      </ul>
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
  nav {
    text-align: center;
    background: #001e43;
  }
  nav ul {
    margin: 0;
    padding: 0;
    height: 50px;
  }
  nav ul li {
    position: relative;
    list-style: none;
    display: inline-block;
    margin: 0 10px 0 0;
    height: 50%;
    width: 10%;
    min-width: 90px;
  }
  .float {
    width: 270px;
    margin: auto;
    overflow: hidden;
  }
  .float li {
    float: left;
  }
  nav ul li a {
    position: absolute;
    top: 50%;
    left: 50%;
    margin: auto;
    text-decoration: none;
    color: #fffff9;
  }

</style>