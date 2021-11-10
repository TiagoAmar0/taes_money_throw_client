<template>
  <div style="height:100vh" class="container is-max-widescreen is-flex is-flex-direction-column is-justify-content-flex-end">
    <footer class="footer">
      <nuxt-link to="/register">
        <b-button type="is-success" expanded outlined>Criar Conta</b-button>
      </nuxt-link>
      <nuxt-link to="/login">
        <b-button type="is-success mt-1" expanded>Iniciar Sessão</b-button>
      </nuxt-link>
    </footer>
  </div>
</template>

<script>
  export default {
    name: 'LandPage'
  }
</script>
