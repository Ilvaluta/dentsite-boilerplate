<template>
  <div class="hero-wrapper">
    <b-row align-h="center">
      <b-container fluid>
        <div class="hero-text">
          <h1 class="hero-title">Lorem ipsum</h1>
          <h5 class="hero-subtitle">Lorem ipsum dolor sit amet consectetur adipisicing elit.</h5>
          <b-btn href="/booking" class="hero-btn">Make an appointment</b-btn>
        </div>
      </b-container>
    </b-row>
  </div>
</template>

<script>

</script>

<style lang="sass">
.hero-wrapper
  height: 60vh
  width: 100%
  background: url('../assets/carousel1.jpg')
  background-size: cover
  background-repeat: no-repeat
  .hero-text
    margin: 184px 0 0 132px
    color: #141414
    .hero-btn
      margin: 16px 0
      padding: 12px
      background: #C9465A
      border: 0
</style>