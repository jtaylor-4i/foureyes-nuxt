<template>
  <v-app>
    <v-card class="overflow-hidden">
      <v-app-bar
        absolute
        shrink-on-scroll
        color="#6A76AB"
        prominent
        src="https://foureyes-web.s3.us-east-2.amazonaws.com/assets/img/logoResize.png"
        fade-img-on-scroll
        scroll-target="#scrolling-techniques-3"
        app
      >
        <v-app-bar-title>
          FOUREYES LABS
        </v-app-bar-title>
        <v-spacer></v-spacer>
        <template v-slot:extension>
          <v-tabs
            fixed-tabs
            color="#fff"
            right
          >
            <v-tab>
              <NuxtLink to="/">HOME</NuxtLink>
            </v-tab>
            <v-tab>
              <NuxtLink to="/services">SERVICES</NuxtLink>
            </v-tab>
            <v-tab>
              <NuxtLink to="/about">ABOUT</NuxtLink>
            </v-tab>
            <v-tab>
              <NuxtLink to="/contact">CONTACT</NuxtLink>
            </v-tab>
          </v-tabs>
        </template>
      </v-app-bar>
      <v-main>
        <v-sheet
          id="scrolling-techniques-3"
          class="overflow-y-auto"
          max-height="100vh"
        >
          <v-container>
            <Nuxt/>

          </v-container>
        </v-sheet>
      </v-main>
      <v-footer app>
        <h3>FOUREYESLABS</h3>
      </v-footer>
    </v-card>
  </v-app>
</template>
