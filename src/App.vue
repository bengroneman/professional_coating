<template>
  <div id="app">
    <pnavigation></pnavigation>

    <pjumbotron id="home">
    </pjumbotron>
    <pservices id="services">
      <b-col>
        <pservicecard image_src="img/assets/professional_coatings-4-edit.jpg" card_title="Interior Painting">
          Painting stuff
        </pservicecard>
      </b-col>
      <b-col>
        <pservicecard image_src="img/assets/professional_coatings-5-edit.jpg" card_title="Finish Coating">
          Lorem Ipsum
        </pservicecard>
      </b-col>
      <b-col>

        <pservicecard image_src="img/assets/professional_coatings-3.jpg" card_title="Magic Coating">
          lorem ipsum
        </pservicecard>
      </b-col>
    </pservices>
     <pcontact id="contact">
     </pcontact>
  </div>
</template>

<script>
import pnavigation from '@/components/global/pNavigation.vue'
import pjumbotron from '@/components/pJumbotron.vue'
import pservices from '@/components/pServices.vue'
import pservicecard from '@/components/pServiceCard.vue'
import pcontact from '@/components/pContact.vue'

export default {
  name: 'app',
  components: {
    pnavigation,
    pjumbotron,
    pservices,
    pservicecard,
    pcontact
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
