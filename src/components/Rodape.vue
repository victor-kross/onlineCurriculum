<template>
  <div id="app">
    <div class="content">
      <!-- Seu conteúdo principal aqui -->
    </div>
    <footer class="footer">
      <div class="container">
        <span>&copy; 2024</span>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
body, html {
  height: 100%;
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  min-height: 92vh;
}

.content {
  flex: 1;
}

.footer {
  color: white;
  padding: 1rem 0;
  bottom: 0;
  width: 100%;
  text-align: center;
}
</style>