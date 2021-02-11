<template>
<b-container>
    <div class="header">
        <b-row>
            <b-col class="header-left"><h5 class="header-text">05 55 55 55 55</h5><font-awesome-icon icon="phone" class="header-left-icon"/></b-col>
            <b-col class="header-img"><b-img src="../assets/dentsiteboilerplateimage.png"></b-img></b-col>
            <b-col class="header-right">
                <font-awesome-icon icon="calendar-alt" class="header-right-icon"/>
                <p class="header-text">Lun - Sam. | 8h30 - 19h00</p>
            </b-col>
        </b-row>
    </div>
</b-container>
</template>

<style lang="sass" scoped>
.header
    margin: 32px 0
    .header-img
        text-align: center
    .header-left, .header-right
        padding-top: 24px
        text-align: center
    .header-text
        display: inline
        padding: 0 8px
    .header-left
        border-right: 2px solid #333
        text-align: right
    .header-right
        border-left: 2px solid #333
        text-align: left

</style>

