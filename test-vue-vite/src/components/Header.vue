<template>
  <header>
    <div class="logo">
      <span class="logo-text">Vestox</span>
    </div>

    <nav class="navbar">
      <ul class="nav-link-list">
        <li class="link-list">Home</li>
        <li class="link-list">Wallets</li>
        <li class="link-list">Transactions</li>
        <li class="link-list">Accounts</li>
        <li class="link-list">Reports</li>
        <li class="link-list">Analytics</li>
        <li class="link-list">Chat</li>
      </ul>
    </nav>

    <div class="login">
      <div class="user-info">
        <img
          src="/JesseGdsWeb - Développeur Web à Mazamet.png"
          alt="Alex Terner"
          class="user-image"
        />
        <span class="user-name">Alex Terner</span>
        <span class="user-email">at@gmail.com</span>
      </div>
      <button class="logout-button">Log out</button>
    </div>
  </header>
</template>

<script setup>
// Importez les éléments nécessaires ici, par exemple des icons ou des images
</script>

<style scoped>
/* Styles pour le header */
header {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background: #ffffff;
}

.logo .logo-text {
  font-weight: bold;
  font-size: 1.5rem;
}

.navbar ul {
  list-style: none;
  display: flex;
  flex-direction: column;
}

.navbar ul li {
  margin-right: 20px;
}

.login {
  display: flex;
}

.user-info {
  display: flex;
  align-items: center;
}

.user-image {
  width: 40px;
  height: 40px;
  border-radius: 50%;
}

.logout-button {
  display: flex;
}
</style>
