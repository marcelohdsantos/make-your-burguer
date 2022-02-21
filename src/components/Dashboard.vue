<template>
  <div id="burger-table">
      <div id="burger-table-heading">
          <div class="order-id">#:</div>
          <div>Cliente:</div>
          <div>Pão:</div>
          <div>Carne:</div>
          <div>Opcionais:</div>
          <div>Ações:</div>
      </div>
  </div>

  <div id="burger-table-rows">
      <div class="burger-table-row">
          <div class="order-number">1</div>
          <dir>João</dir>
          <div>Pão de Trigo</div>
          <div>Maminha</div>
      </div>
      <div>
          <ul>
              <li>Salame</li>
              <li>Tomate</li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
    name: "Dashboard"
}
</script>

<style scoped>

</style>