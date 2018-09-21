<template lang="pug">
  main
    nav
      .nav.cols
        .navCenter.col
          marquee
            a(href="/") Form Cards — Less Design Thinking, More Design Doing 
    section#intro
      .row
        .col6.center
          img(src="/img/cards.png" data-emergence="hidden").isAnimated
        .col6.marT3.marReset
          h2.bolder.indigo Form Cards
          h3 Design principles and prompts for your product team to evaluate user interfaces.
          p *The inks are still wet but if you'd like a sneak peek, signup and we'll host a short workshop!
          no-ssr
            form(data-netlify="true" name="contact" method="POST" action="http://form.cards/thanks.html")
              .inputGroup
                input(type="email" name="email" placeholder="Email")
                button(type="submit") Signup
    section#claim
      .row.padY4.padX7.center.padReset
        .col
          h3 Strategy Decks for Design Lovers        
          h2.bolder Dialog. Make. Collaborate.
          img(src="/img/logoLg.svg" data-emergence="hidden").wid50.isAnimated
          h3 Works better than design jargon
            br
            | …or your money back!
          h1.marT6.marReset.bolder More design doing
</template>
<script>
export default {
  mounted: () => {
    emergence.init();
  },
};
</script>
