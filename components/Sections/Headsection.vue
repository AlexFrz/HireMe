<template>
  <section class="header">
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
.header__text-wrapper {
  width: 80%;
  margin-left: 7.5%;
  transform: translateY(10%);

  span {
    color: $maroon;
  }
}
</style>
