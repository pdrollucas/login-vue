<template>
  <div class="container">
    <div class="jumbotron mt-2">
      <h1 class="display-4">Bem-vindo!</h1>
      <p>Aplição disponível para listagem dos gerentes do nosso banco.</p>
    </div>
    <button class="btn btn-danger" @click="efetuarLogout">Sair</button>
  </div>
</template>

<script>
import { logoutMixin } from '../mixins.js'

export default {
  name: 'home',
  mixins: [logoutMixin]
}
</script>
