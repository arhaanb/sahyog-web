<template>
  <div id="app">
    <div class="container">
      <div class="nav">
        <div>
          <router-link to="/">
            <img
              class="logo"
              draggable="false"
              src="./assets/logo.svg"
              alt
            />
          </router-link>
        </div>
        <div id="right">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
        </div>
      </div>
    </div>

    <router-view />
    <div class="container">
      <footer class="footer">
        <div class="six columns">&copy; Sahyog</div>
        <div class="six columns right">
          <a href="//madewithlove.org.in">Made with &hearts; in India</a>
        </div>
      </footer>
    </div>
  </div>
</template>

<style scoped>
.logo {
  width: 6em;
}

.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.right {
  text-align: right;
}

@media (max-width: 550px) {
  footer.footer {
    text-align: center;
  }
  .right {
    text-align: center;
  }
}
</style>
