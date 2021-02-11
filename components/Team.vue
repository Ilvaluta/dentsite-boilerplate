<template>
  <div class="team-wrapper">
      <b-container> <!-- Nested Container, check for future issues -->
      <h3 class="team-title">Notre Equipe</h3>
    <b-row>
            <b-col>
                <div class="team-member">
                    <b-card
                    title="Dr. Bernard"
                    sub-title="Chirurgien-Dentiste"
                    img-src="../assets/team1.jpg"
                    img-alt="Image"
                    img-top
                    style="max-width: 20rem;"
                    class="mb-2"
                    >
                        <b-card-text>
                        - Diplôme Universitaire d’Implantologie et d’Esthétique Dentaire
                        </b-card-text>
                    </b-card>
                </div>
            </b-col>
            <b-col>
                <div class="team-member">
                    <b-card
                    title="Dr. Bernard"
                    sub-title="Chirurgien-Dentiste"
                    img-src="../assets/team2.jpg"
                    img-alt="Image"
                    img-top
                    style="max-width: 20rem;"
                    class="mb-2"
                    >
                        <b-card-text>
                        - Diplôme Universitaire d’Implantologie et d’Esthétique Dentaire
                        </b-card-text>
                    </b-card>
                </div>
            </b-col>
            <b-col>
                <div class="team-member">
                    <b-card
                    title="Dr. Bernard"
                    sub-title="Chirurgien-Dentiste"
                    img-src="../assets/team1.jpg"
                    img-alt="Image"
                    img-top
                    style="max-width: 20rem;"
                    class="mb-2"
                    >
                        <b-card-text>
                        - Diplôme Universitaire d’Implantologie et d’Esthétique Dentaire
                        </b-card-text>
                    </b-card>
                </div>
            </b-col>
    </b-row>
    </b-container>
  </div>
</template>

<script>

</script>

<style lang="sass">
.team-wrapper
    width: 100%
    margin: 40px 0
    .team-title
        text-align: center
        margin-bottom: 40px
    .team-member
        .card
            border: 0
            .card-title
                color: #C9465A
                

</style>