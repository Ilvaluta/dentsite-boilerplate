<template>
  <div class="footer-wrapper">
    <b-container-fluid>
      <b-row align-h="between">
        <b-col cols="8" offset="1">
          <div class="footer-copyright">Lorem Copyright &copy; 2021</div>
        </b-col>
        <b-col cols="3">
          <div class="footer-links">
            <b-link src="legal" class="legal-link">Privacy</b-link>
            <ul class="footer-socials">
              <li><font-awesome-icon size="2x" :icon="['fab', 'facebook-square']" /></li>
              <li><font-awesome-icon size="2x" :icon="['fas', 'envelope-square']" /></li>
            </ul>
          </div>
        </b-col>
      </b-row>
    </b-container-fluid>
  </div>
</template>

<script>

</script>

<style lang="sass">
.footer-wrapper
  height: 5vh
  width: 100%
  background: #EEE
  overflow: hidden
  .footer-copyright
    padding-top: 8px
  .footer-links
    padding-top: 8px
    .legal-link
      display: inline-block
      float: left
      padding-right: 16px
    .footer-socials
      list-style: none
      li 
        display: inline-block
</style>