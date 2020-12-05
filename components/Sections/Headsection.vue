<template>
  <section v-rellax="{ speed: -7 }" class="header">
    <TheHeader />
    <!-- header -->
    <div class="header__text-wrapper">
      <h1>
        I want big <span>ideas</span><br />
        to be heard, <br />
        and good <span>products</span> <br />to be sold.
      </h1>
    </div>
  </section>
</template>

<script>
import TheHeader from '@/components/UX/TheHeader'
export default {
  components: { TheHeader },
}
</script>

<style scoped lang="scss">
section {
  position: relative;
}

.header {
  background-color: $beige;
  background-attachment: fixed;
}
.header__text-wrapper {
  width: 80%;
  margin-left: 7.5%;
  transform: translateY(10%);

  span {
    color: $maroon;
  }
}
</style>
