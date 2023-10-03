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
          Hi! I’m Peter Winter, PhD. 
        </p>        
        <p class="pt-8 bodyText">  
          I'm a
          <span class='azure--text'> data scientist</span>, 
          <span class='azure--text'> researcher</span>,
          and
          <span class='azure--text'> machine learning engineer</span>.
        </p>

        <p class="pt-4 bodyText">
          I combine design thinking with analytical problem solving to create data-driven solutions for users and stakeholders.

        </p>

        <span v-for="(job, index) in jobs" :key="index">
          <p class="pt-8 bodyText" >
            <span class='gold--text'>{{job.co}} </span> ~ <span class='gold--text'> {{job.title}} </span>
          </p>
          <p class="pt-4 bodyText">
            {{job.desc}}
          </p>
        </span>

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
        </p>
        </v-col>
      </v-row>

      </v-card>
    </v-col>
  </v-row>
</template>

<script>


  export default {
    components: {},
    data () {return {
      jobs: [
        {
          id: 0, 
          co: 'IDEO',
          title: 'Senior Lead Data Scientist',
          desc: 'Inventing new products and services - that are powered by data and AI.'
        },
        {
          id: 1, 
          co: 'Datascope',
          title: 'Data Scientist + Data Engineer',
          desc: 'Building end-to-end ML and analysis pipelines.'
        },
        {
          id: 2, 
          co: 'Northwestern University',
          title: 'Post-doctoral Researcher',
          desc: 'Research on complex sytems, networks, and aging.'
        }
      ],
      skills: {
        subsection: ['skill1', 'skill2']

      }
    }}
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
