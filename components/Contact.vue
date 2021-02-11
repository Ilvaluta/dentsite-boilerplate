<template>
  <div class="contact-location">
    <b-row>
      <b-col cols="4" offset="2">
        <div class="contact-header">
          <h3>Nous Contacter</h3>
          <p>N'hesitez pas à nous contacter</p>
        </div>
        <div class="contact-list">
          <div class="contact-list-item">
            <font-awesome-icon class="contact-list-item-icon" icon="map-marked" size="2x"/> 
            <div class="contact-list-item-text">
              <h5>Notre Addresse</h5>
              <p>21 Avenue du Boulevard 95000 Cergy</p>
            </div>
            </div>
            <div class="contact-list-item">
              <font-awesome-icon class="contact-list-item-icon" icon="phone" size="2x"/>
              <h5>Téléphone</h5>
              <p>05 55 55 55 55</p>
              </div>
            <div class="contact-list-item">
              <font-awesome-icon class="contact-list-item-icon" icon="calendar-alt" size="2x"/>
              <h5>Horaires d'ouverture</h5>
              <p>Lun - Sam. | 8h30 - 19h00</p>
            </div>
          </div>
      </b-col>
      <b-col cols="6">
        <b-img class="google-map" src="../assets/mapsplaceholder.png" fluid-grow />
      </b-col>
    </b-row>
  </div>
</template>


<style lang="sass">
.contact-location
  .contact-header
    margin: 40px 0 40px 56px
  .contact-list
    .contact-list-item
      display: grid
      grid-template-columns: 0.1fr 1.9fr
      grid-template: 1fr 1fr
      gap: 0px 16px
      grid-template-areas: "icon label" "icon text"
      margin: 16px 0
      padding: 8px 2px
      .contact-list-item-icon
        align-self: center
        grid-area: icon
      .contact-list-item-text
        h5
          grid-area: label
        p
          grid-area: text
.google-map
  margin-left: 42px
</style>