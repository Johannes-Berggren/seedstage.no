<template>
  <div>
    <section>
      <v-parallax
        src="header.jpg"
        height="600"
      >
        <v-layout
          column
          align-center
          justify-center
          class="white--text"
        >
          <img
            src="Logo_white.png"
            style="width: 100%; max-width: 900px"
          >
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
        <v-flex
          xs12
          sm4
          class="my-4"
        >
          <div class="text-center">
            <h2 class="headline">
              Portfolio
            </h2>
          </div>
        </v-flex>
        <v-flex xs12>
          <v-layout
            row
            wrap
            justify-center
          >
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
              <img
                src="/horde_logo.png"
                style="max-width: 100px"
              >
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
              <img
                src="/exero_logo.png"
                style="max-width: 100px"
              >
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
            <v-flex
              xs12
              sm6
              md4
              my-5
              investment-logos
            >
              <img src="/livly_logo-01.png" style="max-height: 80px">
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </section>

    <section>
      <v-container grid-list-xl>
        <v-layout
          row
          wrap
          justify-center
          class="my-12"
        >
          <v-flex
            id="contact"
            xs12
          >
            <v-card
              flat
              class="transparent"
              style="width: 290px; margin: auto"
            >
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
.v-card__text {
  padding-top: 5px !important;
  margin-bottom: 20px !important;
}

h2 {
  font-size: 30px;
  text-align: center;
}

a {
  font-family: sans-serif;
  text-decoration: none;
}

.first a {
  font-size: 18px;
}

.second a {
  font-size: 16px;
}

.investment-logos {
  display: flex;
}

.investment-logos img {
  align-self: center;
  margin: auto;
  margin-bottom: 20px;
}

.investment-logos img {
  max-width: 200px;
}

.team {
  text-align: center;
}

.team img {
  border-radius: 100% !important;
  width: 150px;
  height: 150px;
}

.bottom-spacing {
  margin-bottom: 80px !important;
}

.team p {
  margin: 0;
}

.team .role {
  color: grey;
  font-size: 14px;
}
</style>
