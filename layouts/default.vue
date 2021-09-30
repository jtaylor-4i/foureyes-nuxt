<template lang="pug">
  v-app
    v-card.overflow-hidden
      v-app-bar(
        absolute
        shrink-on-scroll
        color="#6A76AB"
        prominent
        src="https://foureyes-web.s3.us-east-2.amazonaws.com/assets/img/logoResize.png"
        fade-img-on-scroll
        scroll-target="#scrolling-techniques-3"
        app
        height="200"
        )
        v-app-bar-title
        v-spacer
        template(v-slot:extension)
          v-tabs(
            fixed-tabs
            color="#fff"
            right
          )
            v-tab
              NuxtLink.link(to="/") HOME
            v-tab
              NuxtLink.link(to="/services") SERVICES
            v-tab
              NuxtLink.link(to="/about") ABOUT
            v-tab
              NuxtLink.link(to="/contact") CONTACT
      v-main
        v-sheet(
          id="scrolling-techniques-3"
          class="overflow-y-auto"
          max-height="100vh")
          v-container
            Nuxt
      v-footer(app)
        h3 FOUREYESLAB
</template>

<style scoped>
  .link {
    text-decoration: none;
    color: #fff;
    font-size: 2em;
  }
</style>
