<template>
  <div>
    <header>
      <h1>Portfolio</h1>
    </header>
    <nav>
      <ul>
        <li><a class="nav-menu-link" href="#">Profile</a></li>
        <li><a class="nav-menu-link" href="#">SKILL</a></li>
        <li><a class="nav-menu-link" href="#">WORKS</a></li>
        <li><a class="nav-menu-link" href="#">CONTACT</a></li>
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
    height: 50px;
  }
  nav ul li {
    width: 15%;
    list-style: none;
    display: inline-block;
  }
  .nav-menu-link {
    display: block;
    margin-top: 14px;
    text-decoration: none;
    height: 50px;
    width: 100%;
    color: #fffff9;
  }

</style>