<template>
  <div id="app">
    <nav class="navbar is-fixed-top is-dark" id="nav">
      <div class="navbar-brand">
        <router-link class="navbar-item title" to="/">Elect Bot</router-link>
      </div>
      <div class="navbar-menu">
        <div class="navbar-start">
          <router-link class="navbar-item" to="/apply">
            <div class="button is-danger">
              Register to Mail-in Vote!
            </div>
          </router-link>
          <div class="dropdown navbar-item">
            <div class="dropdown-trigger">
              <button class="button" aria-haspopup="true" aria-controls="dropdown-menu">
                <span>Langauge Select</span>
                <span class="icon is-small">
                  <i class="fas fa-angle-down" aria-hidden="true"></i>
                </span>
              </button>
            </div>
            <div class="dropdown-menu" id="dropdown-menu" role="menu">
              <div class="dropdown-content">
                <a href="#" class="dropdown-item">
                  Dropdown item
                </a>
                <a class="dropdown-item">
                  Other dropdown item
                </a>
                <a href="#" class="dropdown-item is-active">
                  Active dropdown item
                </a>
                <a href="#" class="dropdown-item">
                  Other dropdown item
                </a>
                <hr class="dropdown-divider">
                <a href="#" class="dropdown-item">
                  With a divider
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
}

#nav {
   position: sticky;
}

#nav a {
  font-weight: bold;
}

#nav a:not(:hover) {
  color: #fff;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
