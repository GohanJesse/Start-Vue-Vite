<template>
  <main class="main-dashboard-content">
    <section class="welcome-section">
      <h1>Hello, Alex</h1>
      <p>Control your investments, income and invoices</p>
    </section>

    <section class="transactions-overview">
      <h2>Transaction overview</h2>
      <div class="transactions">
        <div class="automatic-transactions">
          <span class="number">150</span>
          <span class="label">Automatic transactions</span>
        </div>
        <div class="manual-transactions">
          <span class="number">26</span>
          <span class="label">Manual transactions</span>
        </div>
        <button class="details-button">See details</button>
      </div>
    </section>

    <section class="credit-line">
      <h2>Credit line</h2>
      <!-- Inclure le graphique ou la visualisation de la ligne de crédit -->
    </section>

    <section class="spend-overview">
      <h2>Spend overview</h2>
      <!-- Inclure le graphique ou la visualisation de l'aperçu des dépenses -->
    </section>
  </main>
</template>

<script setup>
// Importation de scripts ou de composants supplémentaires si nécessaire
</script>

<style scoped>
.main-dashboard-content {
  padding: 1rem;
}

.welcome-section {
  margin-bottom: 2rem;
}

.transactions-overview,
.credit-line,
.spend-overview {
  margin-bottom: 1.5rem;
}

.transactions {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.transactions .number {
  font-size: 2rem;
  font-weight: bold;
}

.transactions .label {
  display: block;
}

.details-button {
  display: flex;
}
</style>
