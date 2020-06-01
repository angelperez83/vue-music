<template lang="pug">
  section.hero.is-success
    .hero-header
      header.nav
        .container
          .nav-left
            .nav-item
              strong Music
          .nav-right.nav-menu
            router-link.nav-item(:to="{ name: 'search' }") Buscar
            router-link.nav-item(to="about") Nosotros
    .hero-body
      .container.has-text-centered
        h1.tittle Music!
        h2.subtittle Canciones vuenardas
        pm-player
</template>
<script>
  import PmPlayer from '@/components/Player.vue'

  export default {
    components: { PmPlayer }
  }
</script>