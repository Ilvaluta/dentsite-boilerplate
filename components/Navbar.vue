<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="mx-auto nav-custom">
          <b-nav-item href="#">Accueil</b-nav-item>
          <b-nav-item href="#">Le Cabinet</b-nav-item>
          <b-nav-item href="#">Images</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->

      </b-collapse>
    </b-navbar>
  </div>
</template>

<style lang="sass">
.nav-custom
  .nav-item
    padding: 0 24px
    .nav-link
      text-transform: uppercase
      font-weight: bold 
</style>
