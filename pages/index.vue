<template>
  <v-container>
    <v-layout column align-start my-4>
      <v-flex xs12 sm6 md2>
        <img src="/seedstage_logo_small.png" alt="Seedstage logo" style="width: 100%; max-width: 300px">
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 bottom-spacing>
      <v-flex xs12 my-2>
        <h2>Investments</h2>
        <v-divider />
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <a href="https://sharebox.no">
          <img src="/sharebox_logo.png">
        </a>
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <a href="https://accountflow.no">
          <img src="/accountflow_logo.png">
        </a>
      </v-flex>
      <v-flex xs4 mt-3 mb-3 investment-logos>
        <a href="https://luado.no">
          <img src="/luado_logo.png">
        </a>
      </v-flex>
    </v-layout>

    <v-layout wrap justify-center my-5 team bottom-spacing>
      <v-flex xs12 my-2>
        <h2>Team</h2>
        <v-divider />
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/johannes_berggren.jpeg" alt="Johannes Berggren">
        <p>Johannes Berggren</p>
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/arthur_pogosov.jpeg" alt="Arthur Pogosov">
        <p>Arthur Pogosov</p>
      </v-flex>
      <v-flex xs4 mt-3 mb-3>
        <img src="/hans_webjornsen.jpeg" alt="Hans Webjørnsen">
        <p>Hans Webjørnsen</p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style scoped lang="stylus">
  h2
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

  .investment-logos a
    align-self center
    margin auto

  .investment-logos a img
    max-width 200px

  .team
    text-align center

  .team img
    border-radius 100%
    width 150px
    height 150px

  .bottom-spacing
    margin-bottom 80px !important
</style>
