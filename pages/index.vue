<template>
  <div class="index">
    <Hero />
    <b-container fluid>
      <b-row>
        <b-col sm="12" lg="4" class="services-top left">
          <div class="col-inner">
            <div class="inner-icon">
              <font-awesome-icon icon="tooth" size="3x"/>
            </div>
            <div class="inner-title">  
              <h5>Service</h5>
            </div>
            <div class="inner-text">
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>
        </b-col>
        <b-col sm="12" lg="4" class="services-top center">
          <div class="col-inner">
            <div class="inner-icon">
              <font-awesome-icon icon="teeth-open" size="3x"/>
            </div>  
            <div class="inner-title">  
              <h5>Service</h5>
            </div>
            <div class="inner-text">
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>      
        </b-col>
        <b-col sm="12" lg="4" class="services-top right">
          <div class="col-inner">
            <div class="inner-icon">
              <font-awesome-icon icon="star-of-life" size="3x"/>
            </div>
            <div class="inner-title">  
              <h5>Service</h5>
            </div>
            <div class="inner-text">
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
            </div>
          </div>      
        </b-col>
      </b-row>
    
      <div class="main-text">
        <b-row>
          <b-col>
            <h2 class="main-text-title">Welcome to Lorem</h2>
            <h6 class="main-text-subtitle">We are lorem dentists</h6>
          </b-col>
        </b-row>
        <div class="main-text-body">
          <b-row>
            <b-col cols="5" offset="1">
              <b-img fluid src="../assets/doctors.jpg" />
            </b-col>
            <b-col cols="5" offset="1">
              <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Saepe eveniet nobis, consequuntur officiis amet perferendis velit hic </p>
              <div class="subsection">
                <font-awesome-icon icon="capsules" size="2x" class="main-icon-left"/>
                <h5 class="subsection-title">Lorem</h5>
                <p class="subsection-text">Test</p>
              </div>
              <div class="subsection">
                <font-awesome-icon icon="bacteria" size="2x" class="main-icon-left"/>
                <h5 class="subsection-title">Lorem</h5>
                <p class="subsection-text">Test</p>
              </div>
              <div class="subsection">
                <font-awesome-icon icon="clipboard-list" size="2x" class="main-icon-left"/>
                <h5 class="subsection-title">Lorem</h5>
                <p class="subsection-text">Test</p>
              </div>
              <div class="subsection">
                <b-button href="/cabinet" class="subsection-btn">Le cabinet</b-button> 
              </div>
            </b-col>
          </b-row>
        </div>
      </div>
      <!-- Row to make the imports full width, nested rows inside the components, may need to change in future -->
      <b-row>
        <Services />
        <Team />
        <div class="appointment-banner">
          <b-col>
            <h3>Prise de rendez-vous facilitée</h3>
            <p>Le cabinet vous propose de prendre rendez-vous par téléphone au 05555555, ou bien directement sur le notre site.</p>
            <b-button href="/rendezvous">Prendre Rendezvous</b-button> 
          </b-col>
        </div>
      </b-row>
      <Contact />
    </b-container>
    <Footer />
  </div>
</template>

<script>
export default {}
</script>

<style lang="sass">
.services-top
  padding: 16px 0
  &.left
    background: #17a2b8 
  &.center
    background: #C9465A
  &.right 
    background: #72A98F
.col-inner
  display: grid
  grid-template-columns: 0.5fr 2fr
  grid-template-rows: 1fr 1fr
  gap: 0
  grid-template-areas: "inner-icon inner-title" "inner-icon inner-text"
  color: #f8f8ff
  .inner-icon
    grid-area: inner-icon
    margin: 32px 0 24px 0
    text-align: center
  .inner-title
    align-self: end
    margin-top: 24px
    grid-area: inner-title
    text-align: left
  .inner-text
    grid-area: inner-text
    text-align: left
.main-text
  margin: 48px 0
  .main-text-title, .main-text-subtitle
    text-align: center
  .main-text-subtitle
    margin-bottom: 48px
  .subsection
    padding: 16px 0
    .main-icon-left
      float: left
      margin: 6px
      width: 32px
      height: 32px
    .subsection-title
      color: #C9465A
      font-weight: bold
    .subsection-text
      line-height: 1
    .subsection-btn
      background-color: #17a2b8
      border: 0
      font-size: 1em
      padding: 8px 24px
.appointment-banner
  padding: 16px 0
  text-align: center
  background: #72A98F
  width: 100%
</style>
