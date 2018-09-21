<template lang="pug">
  main
    nav.z1
      .nav.cols
        .navCenter.col
          marquee
            a(href="/") Form Cards — Less Design Thinking, More Design Doing 
    section#intro
      .row
        .col3.center.card.hide
          .content
            .front
              img(src="/img/back.svg" data-emergence="hidden").isAnimated
            .back
              img(src="/img/frontA.svg" data-emergence="hidden").isAnimated
        .col3.center.card.z0.hide
          .content
            .front
              img(src="/img/frontA.svg" data-emergence="hidden").isAnimated
            .back
              img(src="/img/back.svg" data-emergence="hidden").isAnimated
        .col6.marT6.marReset.z1
          h2.bolder.indigo Form Cards
          h3 Design principles and prompts for your product team to evaluate user interfaces.
    section#claim
      .row.padY4.padX7.center.padReset
        .col
          h3 Strategy Decks for Design Lovers        
          h2.bolder.pink Dialog. Make. Collaborate.
          img(src="/img/logoLg.svg" data-emergence="hidden").wid50.isAnimated
          h3 Works better than design jargon
            br
            | …or your money back!
          h1.marT6.marReset.bolder.pink More design doing
</template>
<script>
export default {
  mounted: () => {
    emergence.init();
  },
};
</script>
