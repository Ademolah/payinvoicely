<template>
  <div id="wrapper">
    <nav class="navbar is-dark">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item"><strong>Invoicely</strong></router-link>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">

        </div>
      </div>
    </nav>
  </div>
  <router-view></router-view>
</template>

<style lang="scss">
@import '../node_modules/bulma'
</style>
