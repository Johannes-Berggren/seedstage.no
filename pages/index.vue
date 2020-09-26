<template>
  <div>
    <section>
      <v-parallax src="header.jpg" height="600">
        <v-layout
          column
          align-center
          justify-center
          class="white--text"
        >
          <img src="Logo_white.png" style="width: 100%; max-width: 900px">
          <h1 class="white--text mb-2 display-1 text-center">
            Angel investor collective
          </h1>
          <div class="subheading mb-4 text-center">
            We share knowledge, ideas and dealflow.
          </div>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <v-layout
        column
        wrap
        class="my-12"
        align-center
      >
        <v-flex xs12 sm4 class="my-4">
          <div class="text-center">
            <h2 class="headline">
              Portfolio
            </h2>
          </div>
        </v-flex>
        <v-flex xs12>
          <v-layout row wrap justify-center>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/sharebox_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/accountflow_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/horde_logo.png" style="max-width: 100px">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/luado_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/cavai_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/bagin_logo.jpg">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/logo_boldbooks.jpg">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/exero_logo.png" style="max-width: 100px">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/taasen_microgreens_logo.jpg">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/hubro_education_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/learnlink_logo.png">
            </v-flex>
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/visualyst_logo.png">
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </section>

    <section class="investment-profile">
      <v-layout column align-center justify-center>
        <v-flex xs12 class="my-4">
          <div class="text-center">
            <h2 class="headline">
              Our investment profile
            </h2>
            <p>Companies that have some initial traction.</p>
            <p>Completed FFF and pre-seed rounds.</p>
            <p>If you don't have revenue, you should know how to get it.</p>
          </div>
        </v-flex>
      </v-layout>
    </section>

    <section>
      <v-layout
        wrap
        class="my-12"
        align-center
      >
        <v-flex xs12 class="my-4">
          <div class="text-center">
            <h2 class="headline">
              Members
            </h2>
          </div>
        </v-flex>
        <v-flex xs12>
          <v-layout row wrap align-top justify-center team>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/johannes_berggren.jpeg" alt="Johannes Berggren">

                <div class="headline text-center">
                  Johannes Berggren
                </div>

                <v-card-text>
                  <strong>Software Engineering</strong><br>
                  Systems administration<br>
                  Software architecture<br>
                  Product development<br>
                  Outsourcing
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/arthur_pogosov.jpeg" alt="Arthur Pogosov">

                <div class="headline">
                  Arthur Pogosov
                </div>

                <v-card-text>
                  <strong>Digital Marketing</strong><br>
                  Conversions and bidding<br>
                  Reporting and analysis<br>
                  Business development<br>
                  Project management
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/hans_webjornsen.jpeg" alt="Hans Webjørnsen">

                <div class="headline text-center">
                  Hans Webjørnsen
                </div>

                <v-card-text>
                  <strong>Finance</strong><br>
                  Valuation and due dilligence<br>
                  Budgets and forecasts<br>
                  Financial reporting<br>
                  Audits
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/christian_storm.jpeg" alt="Hans Webjørnsen">

                <div class="headline text-center">
                  Christian Storm
                </div>

                <v-card-text>
                  <strong>Finance and Treasury</strong><br>
                  Financial reporting<br>
                  Cash management<br>
                  Asia connections<br>
                  Financing
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/martin_jorgensen.jpg" alt="Hans Webjørnsen">

                <div class="headline text-center">
                  Martin Jørgensen
                </div>

                <v-card-text>
                  <strong>Fintech</strong><br>
                  Hospitality and travel<br>
                  Digital transformation<br>
                  Saas companies
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/hakon_kristiansen.jpeg" alt="Hans Webjørnsen">

                <div class="headline text-center">
                  Håkon Kristiansen
                </div>

                <v-card-text>
                  <strong>Digital Marketing</strong><br>
                  Search Engine Optimization<br>
                  Conversion Optimization<br>
                  Business Development<br>
                  Business Strategy
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm6 md4 lg3>
              <v-card flat class="transparent">
                <img src="/ola_svalheim.jpeg" alt="Hans Webjørnsen">

                <div class="headline text-center">
                  Ola Leithe Svalheim
                </div>
              </v-card>
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </section>

    <section>
      <v-container grid-list-xl>
        <v-layout row wrap justify-center class="my-12">
          <v-flex id="contact" xs12>
            <v-card flat class="transparent" style="width: 290px; margin: auto">
              <v-list class="transparent">
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">
                      mdi-map-marker
                    </v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>Oslo, Norway</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">
                      mdi-email
                    </v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>
                      hello@seedstage.no
                    </v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
  </div>
</template>

<style scoped lang="stylus">
.v-card__text
  padding-top 5px !important
  margin-bottom 20px !important

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
  margin-bottom 20px

.investment-logos img
  max-width 200px

.team
  text-align center

.team img
  border-radius 100% !important
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
