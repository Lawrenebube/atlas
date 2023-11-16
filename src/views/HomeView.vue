<script setup>
import SupperClub from '../components/supperClub.vue';
import highFlyer from '../components/highFlyer.vue';
import womanVideo from '../components/womanVideo.vue';
import powerCoupleVue from '../components/powerCouple.vue';
import trulyPersonal from '../components/trulyPersonal.vue';
import atlasBenefit from '../components/atlasBenefit.vue';
import footerLinks from '../components/footerLinks.vue';
import footerComponent from '../components/footerComponent.vue';
import inSure from '../components/insuranceComponent.vue'
</script>

<template>

    <div class="home">
      <section class="hero">
        <h1>No Limits</h1>
        <div class="heros-video-container">

        <video autoplay muted>
          <source src="../assets/atlas-card.webm" type="video/mp4" />
        </video>
      </div>

        <article>
          This is your friend who scores the hottest tables in town, your passport to weekend
          getaways, and your guest pass to must-see events. All brilliantly brought together in a card
          and app of uncompromising beauty and utility. This is the beginning of a journey to a world
          with no limits.
        </article>
        <p>This is Atlas.</p>
      </section>

      <SupperClub />
      <highFlyer />
      <womanVideo/>
      <powerCoupleVue/>
      <trulyPersonal/>
      <atlasBenefit/>
      <footerLinks/>
      <footerComponent/>
      <inSure/>
    </div>
  
  
</template>

<script>
export default {
 
};
</script>
<style scoped >
  .home {
  }
</style>


