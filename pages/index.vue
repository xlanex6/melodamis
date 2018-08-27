<template lang="pug">
  div
    section.hero.is-medium.is-danger.is-bold.is-large
      .container
        nav.level.is-transparent
            .level-left Home
            .level-right Agenda Repertoire
        .hero-body
          .container
            h1.title 
              | Melodamis
            h2.subtitle
              | Chorale de Charnay-les-macon
    section.section
      .container
        .columns
          .column
            .card
              .card-content.has-text-centered
                i.far.fa-clock
                h3
                  | voici ma card de merde
          .column
            .card
              .card-content.has-text-centered
                i.fas.fa-map-marker-alt
                h3
                  | voici ma card de merde
          .column
            .card
              .card-content.has-text-centered
                i.fas.fa-map-marker-alt
                h3
                  | voici ma card de merde
    section.section 
      .container
        

</template>

<script>


export default {
  components: {
    
  }
}
</script>

<style lang="scss">
  i {
    font-size: 35px;
  }
</style>

