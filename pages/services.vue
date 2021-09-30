<template lang="pug">
  v-container
    template
      v-parallax(
        dark
        src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
      )
        v-row(
          align="center"
          justify="center"
        )
          v-col(
            class="text-center"
            cols="12"
          )
            h1.text-h3.font-weight-thin.mb-4 OUR SERVICES
            h3.subheading Bring your project to life
    v-divider
    v-row
      v-card
        h3.text-center Agile and Lean practices are best suited for highly-complex rapidly changing projects. We leverage those principals by focusing on collaboration, ability to adapt to changes and to technical insights into business based decisions
          v-spacer
          v-divider
    v-container.fill-height(
      fluid
      style="min-height: 500px"
    )
      v-row
        v-col
          v-card
            v-img(
              src="https://picsum.photos/350/165?random"
              height="125"
              class="grey darken-4"
            )
    v-row
      v-card
        h4.text-center Our clients have needs that span across all levels of the software development lifecycle, from development to deployed. We assist in all aspects in delivering software applications including DevOps, integration, architecture, development and design
    v-row
      v-col.purple.lighten-5
        h2 DevOps
        p.
          With our combination of cultural philosophies, knowledge, and team we can increase an organizations ability to deliver applications and services with high quality. Guiding the evolution and improving a company's product so that they may produce at a faster pace.

      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )
    v-row
      v-col.purple.lighten-5
        h2 UI/UX Design
        p.
          We have a passion for creativity and when it comes to UI/UX design we continue to hone that passion and create exciting products for our customers. To maximize utilization and customer satisfaction of our designs, we take into consideration multiple target devices and operating systems

      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )
    v-row
      v-col.purple.lighten-5
        h2 Data and Analytics
        p.
          We love data. The process of identifying patterns and trends, analyzing these results and providing our findings to our clients so that we can establish the business needs and use this data to work on those needs.

      v-col
        v-sheet(color="white", elevation="3", height="500", shaped, width="100%")
          v-img(
            lazy-src="https://picsum.photos/id/11/10/6"
            src="https://picsum.photos/id/11/500/300"
            height="100%"
            width="100%"
          )

</template>
