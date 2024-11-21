<template>
  <div class="login-page-container">
    <div class="welcome-section">
      <div class="welcome-text">
        <h1>Selamat Datang di Halaman Login</h1>
        <h2>Rafaella Christiant Zahnareysa</h2>
        <h2>40622100107</h2>
      </div>
      <div class="login-form">
        <LoginComponent />
      </div>
    </div>
  </div>
</template>

<script>
import LoginComponent from '@/components/LoginComponent.vue'

export default {
  components: {
    LoginComponent,
  },
}
</script>

<style scoped>
.welcome-section {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 50px; /* Menambahkan spasi antara teks dan form */
  width: 80%; /* Lebar keseluruhan container */
}

.welcome-text {
  flex: 1;
  text-align: left;
}

.login-form {
  flex: 1;
}
</style>
