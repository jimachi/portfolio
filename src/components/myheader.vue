<template>
  <div>
    <header>
      <h1>Portfolio</h1>
    </header>
    <nav>
      <ul class="nav">
        <li><font-awesome-icon class="nav-icon" icon="user" /><a href="#">Profile</a></li>
        <li><font-awesome-icon class="nav-icon" icon="pen" /><a href="#">SKILL</a></li>
        <li><font-awesome-icon class="nav-icon" icon="user" /><a href="#">WORKS</a></li>
        <li><font-awesome-icon class="nav-icon" icon="envelope" /><a href="#">CONTACT</a></li>
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
    height: 40px;
  }
  nav ul li {
    list-style: none;
    display: inline-block;
    width: 18%;
    min-width: 90px;
  }
  nav ul li a {
    text-decoration: none;
    color: #fffff9;
  }
  .nav-icon {
    margin-right: 5px;
    color: #fffff9;
  }

</style>