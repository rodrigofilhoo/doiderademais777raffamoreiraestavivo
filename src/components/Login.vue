<template>
  <main>
    <form>
      <!-- email input -->
      <div data-mdb-input-init class="form-outline mb-4">
        <input type="email" id="emailInput" class="form-control" />
        <label class="form-label" for="emailInput">E-mail</label>
      </div>

      <!-- password input -->
      <div data-mdb-input-init class="form-outline mb-4">
        <input type="password" id="passwordInput" class="form-control" />
        <label class="form-label" for="passwordInput">Senha</label>
      </div>

      <!-- submit button -->
      <a href="../App.vue" type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-primary btn-block mb-4">Entrar</a> 
    </form>
  </main>
</template>
