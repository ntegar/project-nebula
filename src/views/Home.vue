<template>
  <div class="home">
      <section>
        <v-container>
          <v-layout class="white--text" >
          <h1 class="text-xs-left" style="font-size: 80px;">Hi! <br> I am <b> Nabil </b></h1>

          </v-layout>
        </v-container>
      </section>

      <section style="background:white;">
        <v-layout
          column
          wrap
          align-center
        >
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline">The best way to start developing</h2>
              <span class="subheading">
                Cras facilisis mi vitae nunc 
              </span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">color_lens</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Material Design</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">flash_on</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Fast development</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">build</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Completely Open Sourced</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section style="background: #f3f6f9;">
        <v-container>
          <v-layout row >
              <v-flex xs6>
                  <h1>Your daily jack of all trades</h1>
              </v-flex>
              <v-flex xs6>
                  <v-chip color="white">💰 Business</v-chip>
                  <v-chip color="white">💻 Tech</v-chip>
                  <v-chip color="white">🗣️ Public Speaking</v-chip>
                  <v-chip color="white">🏀 Basketball</v-chip>
                  <v-chip color="white">🎸 Music</v-chip>
                  <v-chip color="white">😄 Fun</v-chip>
                  <v-chip color="white">🇮🇩 Indonesian</v-chip>
                  <v-chip color="white">🇺🇸 English</v-chip>
                  <v-chip color="white">🇳🇱 Dutch</v-chip>
              </v-flex>
          </v-layout>
          </v-container>
      </section>

      <section style="background:white;">
        <v-container grid-list-xl>

        </v-container>
      </section>

       <section style="background: #f3f6f9;">
        <v-container>
          <v-layout row justify-center style="margin-bottom: 50px">
          <h1>Tune in some music! 🎶</h1>
          </v-layout>
          <v-layout row justify-center>
           <iframe src="https://open.spotify.com/embed/user/ntegar/playlist/17r8GfwFeiPO9OB0iiPDj3" width="700" height="600" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
          </v-layout>
        </v-container>
      </section>
  </div>
</template>

<style scoped>

section {
  padding-top: 50px;
  padding-bottom: 50px;
}

h1 {
  font-family: 'Lato', sans-serif;
  font-weight: bold;
  font-size: 50px;
}
</style>


