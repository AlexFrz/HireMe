<template>
  <section class="business">
    <div class="business__text1">
      <h2>
        Your website should <br />
        turn visitors into <br />
        <span>engaged</span> <span class="span2">customers</span>.
      </h2>
    </div>
    <div class="business__text2">
      <h2>
        It’s like having a top <br />
        sales rep working
      </h2>
    </div>
    <h2 class="business__text3">
      <span
        >24 hours a day,<br />
        7 days a week.</span
      >
    </h2>

    <BaseButton>Hire me</BaseButton>
  </section>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
section {
  @include sm {
    height: 220vh;
  }
  @include md {
    height: 130vh;
  }
}

.business {
  width: 75%;
  margin: auto;
  justify-content: center;
  text-align: center;
  @include sm {
    padding-top: 15%;
  }
  @include md {
    padding-top: 5%;
  }
}

.business__text2 {
  padding-top: 5%;
  padding-bottom: 5%;
}

.business__text3 {
  padding-bottom: 5%;
}

span {
  color: $maroon;
}
</style>
