<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <div class="navbar-nav mx-auto">
          <i class="nav-item nav-link bi bi-linkedin" @click="goTo('linkedin')"></i>
          <i class="nav-item nav-link bi bi-instagram" @click="goTo('instagram')"></i>
          <i class="nav-item nav-link bi bi-envelope-at-fill" @click="goTo('email')"></i>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    goTo(page) {
      switch (page) {
        case 'linkedin':
          window.location.href = 'https://www.linkedin.com/in/victor-manoel-b61185214';
          break;
        case 'instagram':
          window.location.href = 'https://instagram.com/victor.kross';
          break;
        case 'email':
          window.location.href = 'mailto:victormanoel1227@hotmail.com';
          break;
      }
    }
  }
}
</script>

<style scoped>
.navbar-nav {
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}
.nav-item {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 10px;
}
.nav-link {
  cursor: pointer;
  font-size: 1.5rem;
}
</style>
