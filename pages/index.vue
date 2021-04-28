<template>
  <v-row justify="start">
    <v-col cols=12 sm=10 md=6 xl=4>
      <v-card class='transparent'>

        <v-card outlined>
          <v-img>
            <v-icon dark x-large>mdi-cat</v-icon>
          </v-img>
        </v-card>

        <p class="pt-8 bodyText">
          Hi! I’m Peter Winter, PhD,
          <span class='azure--text'> data scientist </span> + <span class='azure--text'> designer </span>.
        </p>

        <p class="pt-4 bodyText">
          I combine design thinking with analytical problem solving to create data-driven solutions for users and stakeholders.
        </p>

        <p class="pt-8 bodyText">
          <span class='gold--text'>IDEO </span> ~ <span class='gold--text'> Lead Data Scientist </span> + <span class='gold--text'> Designer </span>
        </p>

        <p class="pt-4 bodyText">
          I lead design teams to tackle complex challenges for clients across industries, including healthcare, finance, and food.
        </p>


        <p class="pt-8 bodyText">
          <a class='aquamarine--text' href="https://www.lemongrass.team/" target='_blank'>Lemongrass</a> ~ <span class='aquamarine--text'> Co-Creator </span> + <span class='aquamarine--text'> Backend Developer </span>
        </p>
        <p class="pt-4 bodyText">
          Team brainstorming web app. I designed the backend and user experience, including interactive data visualizations.
        </p>

        <p class="pt-8 bodyText">
          <span class='lavendar--text'>Skills</span>
        </p>
        <v-row>
        <v-col cols=1 class='pa-0' align-self='start'>
          <p class="pt-4 bodyText">
            <span class='lavendar--text'>~ </span>
          </p>
          </v-col>
          <v-col cols=11 class='pa-0'>
          Team brainstorming web app. I designed the backend and user experience, including interactive data visualizations.
        </p>
        </v-col>
      </v-row>


      </v-card>
    </v-col>
  </v-row>
</template>

<script>


export default {
  components: {

  }
}
</script>

<style>
/* colors */
.transparent {
  .background-color: transparent !important
}

.azure--text {color: #00acdb !important; }
.gold--text {color: #ffd11a !important; }
.aquamarine--text {color: #85ffc7 !important; }
.lavendar--text {color: #CFBFF7 !important; }

.rich-black {background-color: #0d0d0d !important; }

/* typeface */
.headText {
  font-family: 'Fira Mono', 'Courier', 'sans-serif' !important;
  font-size: 2.6rem !important;
  line-height: 3rem !important;
}
.subHeadText {
  font-family: 'Fira Mono', 'Courier', 'sans-serif' !important;
  font-size: 2rem !important;
  line-height: 2.4rem !important;
}
.bodyText {
  font-family: 'Fira Mono', 'Courier', 'sans-serif' !important;
  font-size: 1.4rem !important;
  line-height: 1.8rem !important;
}

</style>
