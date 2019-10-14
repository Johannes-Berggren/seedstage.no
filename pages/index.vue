<template>
  <v-container>
    <v-layout column align-start my-4>
      <v-flex xs12 sm6 md2>
        <img src="/seedstage_logo_blue_small.png" alt="Seedstage logo" style="width: 100%; max-width: 300px">
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 bottom-spacing style="text-align: center">
      <v-flex xs4 mt-3 mb-3>
        <p>Seedstage is an angel investor collective. We share knowledge, ideas and dealflow.</p>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 bottom-spacing>
      <v-flex xs12 my-2>
        <h2>We've invested in...</h2>
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/sharebox_logo.png">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/accountflow_logo.png">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/luado_logo.png">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/cavai_logo.png">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/bagin_logo.jpg">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/logo_boldbooks.jpg">
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <img src="/exero_logo.png" style="max-width: 100px">
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 team bottom-spacing>
      <v-flex xs12 my-2>
        <h2>Who are we?</h2>
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/johannes_berggren.jpeg" alt="Johannes Berggren">
        <p>Johannes Berggren</p>
        <p class="role">
          Learnlink
        </p>
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/arthur_pogosov.jpeg" alt="Arthur Pogosov">
        <p>Arthur Pogosov</p>
        <p class="role">
          Oslo Technology Consulting
        </p>
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/hans_webjornsen.jpeg" alt="Hans Webjørnsen">
        <p>Hans Webjørnsen</p>
        <p class="role">
          CFO, Hafslund
        </p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style scoped lang="stylus">
  h2
    font-size 30px
    text-align center

  a
    font-family sans-serif
    text-decoration none

  .first a
    font-size 18px

  .second a
    font-size 16px

  .investment-logos
    display flex

  .investment-logos img
    align-self center
    margin auto

  .investment-logos img
    max-width 200px

  .team
    text-align center

  .team img
    border-radius 100%
    width 150px
    height 150px

  .bottom-spacing
    margin-bottom 80px !important

  .team p
    margin 0

  .team .role
    color grey
    font-size 14px
</style>
