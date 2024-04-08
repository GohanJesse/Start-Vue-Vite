<template>
  <aside class="sidebar">
    <!-- Zone de recherche -->
    <div class="search-container">
      <input type="search" placeholder="Search something" />
      <button class="search-button">
        <!-- Icône de loupe -->
      </button>
    </div>

    <!-- Promotion ou plan d'abonnement -->
    <div class="promotion">
      <h3>$7.99</h3>
      <p>Choose the best plan for you!</p>
    </div>

    <!-- Liste des demandes -->
    <div class="requests">
      <h4>Requests</h4>
      <button class="filter-button">Filter</button>
      <ul>
        <!-- Liste d'éléments résultants du filtre -->
        <li>
          <span class="request-type">Travel expenses</span>
          <span class="request-amount">$2K</span>
        </li>
        <li>
          <span class="request-type">Office supplies</span>
          <span class="request-amount">$110</span>
        </li>
        <li>
          <span class="request-type">Team-building</span>
          <span class="request-amount">$200</span>
        </li>
        <li>
          <span class="request-type">Workshop</span>
          <span class="request-amount">$100</span>
        </li>
        <li>
          <span class="request-type">Prnting Services</span>
          <span class="request-amount">$80</span>
        </li>
      </ul>
      <button class="see-all-button">See all</button>
    </div>
  </aside>
</template>

<script setup>
// Logique de composant ici
</script>

<style scoped>
.sidebar {
  display: flex;
  flex-direction: column;
}

.search-container {
  /* Styles de votre conteneur de recherche */
  display: flex;
}

.search-container input[type="search"] {
  /* Styles de votre champ de recherche */
  background-color: beige;
}

.search-button {
  /* Styles pour votre bouton de recherche */
  display: flex;
}

.promotion {
  /* Styles pour votre section de promotion */
  display: flex;
}

.requests {
  /* Styles pour votre liste de demandes */
  display: flex;
  flex-direction: column;
}

.requests ul {
  /* Styles pour votre liste */
  list-style-type: none;
  padding: 0;
}

.requests li {
  /* Styles pour chaque élément de la liste de demandes */
  display: flex;
  justify-content: space-between;
  /* Plus de styles ici */
}

.see-all-button {
  /* Styles pour votre bouton 'See all' */
  display: flex;
}
</style>
