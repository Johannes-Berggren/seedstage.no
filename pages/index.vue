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
          <h1 class="white--text mb-2 display-1 text-center">Seedstage is an angel investor collective</h1>
          <div class="subheading mb-4 text-center">We share knowledge, ideas and dealflow.</div>
          <v-btn
            class="mt-12"
            color="blue"
            dark
            large
            href="#contact"
          >
            Get in touch
          </v-btn>
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
            <h2 class="headline">Portfolio</h2>
            <span class="subheading">
                Our collective investments
              </span>
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
          </v-layout>
        </v-flex>
      </v-layout>
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
            <h2 class="headline">Members</h2>
            <span class="subheading">
                We're here to help our portfolio companies grow
              </span>
          </div>
        </v-flex>
        <v-flex xs12>
          <v-container grid-list-xl>
            <v-layout row wrap align-top team>
              <v-flex xs12 md4>
                <v-card flat class="transparent">
                  <v-card-text class="text-center">
                    <img src="/johannes_berggren.jpeg" alt="Johannes Berggren">
                  </v-card-text>
                  <v-card-title primary-title class="layout justify-center">
                    <div class="headline text-center">Johannes Berggren</div>
                  </v-card-title>
                  <v-card-text>
                    <strong>Software Engineer</strong><br>
                    Technical expertise.
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 md4>
                <v-card flat class="transparent">
                  <v-card-text class="text-center">
                    <img src="/arthur_pogosov.jpeg" alt="Arthur Pogosov">
                  </v-card-text>
                  <v-card-title primary-title class="layout justify-center">
                    <div class="headline">Arthur Pogosov</div>
                  </v-card-title>
                  <v-card-text>
                    <strong>Digital Marketing Consultant</strong><br>
                    Digital marketing expertise.
                  </v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 md4>
                <v-card flat class="transparent">
                  <v-card-text class="text-center">
                    <img src="/hans_webjornsen.jpeg" alt="Hans Webjørnsen">
                  </v-card-text>
                  <v-card-title primary-title class="layout justify-center">
                    <div class="headline text-center">Hans Webjørnsen</div>
                  </v-card-title>
                  <v-card-text>
                    <strong>CFO</strong><br>
                    Finance and economics expertise.
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>
        </v-flex>
      </v-layout>
    </section>

    <!--    <section>-->
    <!--      <v-parallax src="section.jpg" height="380">-->
    <!--        <v-layout column align-center justify-center>-->
    <!--          <div class="headline white&#45;&#45;text mb-4 text-center">Web development has never been easier</div>-->
    <!--          <em>Kick-start your application today</em>-->
    <!--          <v-btn-->
    <!--            class="mt-12"-->
    <!--            color="blue lighten-2"-->
    <!--            dark-->
    <!--            large-->
    <!--            href="#contact"-->
    <!--          >-->
    <!--            Get Started-->
    <!--          </v-btn>-->
    <!--        </v-layout>-->
    <!--      </v-parallax>-->
    <!--    </section>-->

    <section>
      <v-container grid-list-xl>
        <v-layout row wrap justify-center class="my-12">
          <!--          <v-flex xs12 sm4>-->
          <!--            <v-card flat class="transparent">-->
          <!--              <v-card-title primary-title class="layout justify-center">-->
          <!--                <div class="headline">Company info</div>-->
          <!--              </v-card-title>-->
          <!--              <v-card-text>-->
          <!--                Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.-->
          <!--                Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.-->
          <!--                Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.-->
          <!--              </v-card-text>-->
          <!--            </v-card>-->
          <!--          </v-flex>-->
          <v-flex xs12 sm4 offset-sm1 id="contact">
            <v-card flat class="transparent">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">Contact us</div>
              </v-card-title>
              <!--              <v-card-text>-->
              <!--                Let's start the conversation-->
              <!--              </v-card-text>-->
              <v-list class="transparent">
                <!--                <v-list-item>-->
                <!--                  <v-list-item-action>-->
                <!--                    <v-icon class="blue&#45;&#45;text text&#45;&#45;lighten-2">mdi-phone</v-icon>-->
                <!--                  </v-list-item-action>-->
                <!--                  <v-list-item-content>-->
                <!--                    <v-list-item-title>777-867-5309</v-list-item-title>-->
                <!--                  </v-list-item-content>-->
                <!--                </v-list-item>-->
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">mdi-map-marker</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>Oslo, Norway</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">mdi-email</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>hello@seedstage.no</v-list-item-title>
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
