<template>
  <section class="testimonials">
    <div class="text">
      <h3>
        « Alex is simply one of the most rigorous persons that I know. Work done
        with perfect timing, with a lot of communication to converge for the
        best into exactly what we want and need… »
      </h3>
      <h2 class="ceo">- Ayoub Namrani, CEO</h2>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
section {
  background-color: $black;
  @include sm {
    height: 120vh;
  }
  @include md {
    height: 60vh;
  }
  @include lg {
    height: 100vh;
  }
}

.testimonials {
  color: $beige;
}

h3,
h2 {
  font-family: 'Montserrat';
  font-weight: 300;
  font-size: 35px;
}

h2 {
  color: $maroon;
}

.text {
  width: 75vw;
  justify-content: center;
  align-content: center;
  margin: auto;
  padding-top: 17.5%;
}

.ceo {
  padding-top: 10%;
  padding-left: 55%;
}
</style>
