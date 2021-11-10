<template>
  <div style="height: 100vh" class="container is-max-widescreen is-flex is-flex-direction-column is-justify-content-space-between">
    <section class="section">
      <h2 class="title is-4 has-text-justified">Iniciar Sessão no Money Throw</h2>
      <p class="subtitle is-6 has-text-justified">Para inicar sessão, introduza o seu número de telemóvel registado</p>

      <div class="field">
        <label class="label">Nº de Telemóvel</label>
        <div class="control">
          <input class="input" type="text" placeholder="Nº de Telemóvel" />
        </div>
      </div>
      <div class="field">
        <label class="label">Password</label>
        <div class="control">
          <input class="input" type="password" placeholder="Password" />
        </div>
      </div>
    </section>
    <footer class="footer">
      <nuxt-link to="/login">
        <b-button type="is-success mb-1" expanded>Iniciar Sessão</b-button>
      </nuxt-link>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>
