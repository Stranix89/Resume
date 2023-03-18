<template>
  <nav>
    <div class="navbar">
      <div class="nav-links" :class="{opened: menuIsActive}">
        <ul class="links">
          <li>
            <a href="/">
              Персональная информация
              <hr/>
            </a>
          </li>
          <li>
            <a href="/AboutMe">
              Обо мне
              <hr/>
            </a>
          </li>
          <li>
            <a href="/MyExperienceSkills">
              Мой опыт и навыки
              <hr/>
            </a>
          </li>
          <li>
            <a href="/portfolio">
              Портфолио
              <hr/>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {
      menuIsActive: false
    }
  },
  methods: {
    menuEventButton () {
      this.menuIsActive = !this.menuIsActive
    }
  }
}
</script>

<style scoped>
nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 70px;
  background: #242524;
  z-index: 100000;
}

nav .navbar {
  height: 100%;
  max-width: 1200px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 0 50px;
}
nav .navbar .nav-links {
  height: 100%;
  line-height: 70px;
  vertical-align: middle;
}
nav .navbar .nav-links .links {
  display: flex;
}
nav .navbar .nav-links .links li {
  position: relative;
  display: flex;
  align-items: center;
  list-style: none;
  padding: 0 14px;
}
nav .navbar .nav-links .links li a {
  height: 100%;
  color: #fff;
  text-decoration: none;
  white-space: nowrap;
  font-size: 16px;
  font-weight: 500;
  border-bottom: 0px solid transparent;
  transition: all 0.4s ease;
}
nav .navbar .nav-links .links li:hover a {
  color: #04ed93;
}
nav .navbar .nav-links .links li a hr {
  width: 0px;
  display: hidden;
  border: none;
  border-radius: 70px;
  height: 1.8px;
  background: #04ed93;
  transform: translateY(-1300%);
  transition: all 0.4s ease;
}

nav .navbar .nav-links .links li:hover a hr {
  display: block;
  width: 100%;
  transition: all 0.4s ease;
}

nav .navbar .bx-menu,
nav .navbar .nav-links .sidebar-logo .logo_name,
nav .navbar .sidebar-logo img,
nav .navbar .nav-links .sidebar-logo .bx-x {
  display: none;
}

@media (max-width: 954px) {
  nav .navbar {
    max-width: 100%;
    padding: 0 25px;
  }
  nav .navbar .nav-links .links li {
    padding: 0 10px;
  }
  nav .navbar .nav-links .links li a {
    font-size: 15px;
  }
}

@media (max-width: 800px) {
  nav .navbar .nav-links {
    display: block;
    position: fixed;
    background: #242524;
    top: 0;
    left: -300px;
    max-width: 270px;
    width: 100%;
    padding: 20px;
    line-height: 40px;
    transition: all 0.4s ease;
  }

  nav .navbar .nav-links.opened {
    left: 0;
  }

  nav .navbar .nav-links .sidebar-logo {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  nav .navbar .bx-menu,
  nav .navbar .nav-links .sidebar-logo .logo_name,
  nav .navbar .nav-links .sidebar-logo .bx-x {
    color: #04ed93;
    font-size: 25px;
    font-weight: 500;
    display: block;
  }

  nav .navbar .sidebar-logo img {
    width: 50px;
    height: 50px;
    display: block;
  }

  nav .navbar .nav-links .links {
    display: block;
    margin-top: 20px;
  }

  nav .navbar .nav-links li a hr,
  nav .navbar .nav-links li:hover a hr {
    display: none;
    width: 0px;
    background: transparent;
  }
  nav .navbar .nav-links .links li {
    display: block;
    border-bottom: none;
  }

  nav .navbar .bx-menu {
    cursor: pointer;
  }
}
</style>
