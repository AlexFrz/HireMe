<template>
  <div class="landingpage">
    <Headsection />
    <SuperPowers />
    <NumericRevolution />
    <Business />
    <Projects />
    <Me />
    <Testimonials />
    <HireMe />
  </div>
</template>

<script>
import Business from '../components/Sections/Business.vue'
import Headsection from '../components/Sections/Headsection.vue'
import HireMe from '../components/Sections/HireMe.vue'
import Me from '../components/Sections/Me.vue'
import NumericRevolution from '../components/Sections/NumericRevolution.vue'
import Projects from '../components/Sections/Projects.vue'
import SuperPowers from '../components/Sections/SuperPowers.vue'
import Testimonials from '../components/Sections/Testimonials.vue'

export default {
  components: {
    Headsection,
    NumericRevolution,
    SuperPowers,
    Business,
    Projects,
    Me,
    Testimonials,
    HireMe,
  },
}
</script>

<style lang="scss" scoped>
.landingpage {
  background-color: $beige;
}
</style>
