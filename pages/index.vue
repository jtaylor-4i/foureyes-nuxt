<template lang="pug">
  v-container
    v-row
      v-img(
        src="https://foureyes-web.s3.us-east-2.amazonaws.com/assets/img/laptop-stock-purple.png",
        alt="landing page header",
        width="100%",
        height="400"
      )
        div.intro-container
          h2.text-center.title-text Bring your technology to life
          h3.text-center.title-text Solve your complex business challenges through technology.
          h3.text-center.title-text Custom software development to bring your projects to life.

    v-spacer
      h1.text-center.foureyes IMAGINE - INVENT - INNOVATE - IMPROVE

    v-row
      v-col
        h2.text-center Our Mission
        p.text-center.
          We created Foureyes Labs with the goal to help people and organizations innovate and
          improve their existing technology projects and infrastructure and to imagine and invent
          new ideas through technology. Bringing that to life through those 4 I’s, with a
          relentless focus on client satisfaction, gets us out of bed in the morning. Due to our
          levels of experience in technology leadership and as individual contributors, we can
          help bring your technology projects to the highest standards of implementation,
          execution, optimization, and performance.

      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )
    v-row
      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )
      v-col
        h2.text-center Why Foureyes
        p.text-center.
          At Foureyes Labs, our technology leaders and developers have 35+ years combined
          experience and specialize in creating innovative solutions, driven to solve problems
          through platform development, DevOps, system administration, back-end development,
          front-end development, cloud application development, enterprise architecture, and more.
          Our team’s history includes working at Amazon, Google, Johnson & Johnson, etc. and have
          created and lead multiple startups that have been acquired by some of the biggest
          players in the game. We know a thing or two about bringing concepts to life, and doing
          so by solving the business need through technology. Our team specializes further in
          cloud applications, large enterprise systems, web and mobile applications, data
          integrations, and more.

    v-row
      v-col
        h2.text-center Some of our happy clients
        p.text-center.
          Do we have any testimonials to put here? Any ideas on what we want to put on this page
          so that we can maybe explain what we want the people who visit this site to be able to
          see how our clients have reacted to our services.

      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
        }
      ]
    }
  }
}
</script>

<style>
.title-text {
  color: #fff;
  line-height: 2em;
}

.intro-container {
  margin-top: 5em;
}

.foureyes {
  padding: 3em 0 3em 0;
}
</style>
