<template>
  <section class="powers">
    <ul>
      <li><h1>UI/UX Design</h1></li>
      <li><h1>Web Development</h1></li>
      <li><h1>Brand Identity</h1></li>
      <li><h1>Design Sprints</h1></li>
      <li><h1>Digital Marketing</h1></li>
    </ul>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
section {
  @include sm {
    height: 45vh;
  }

  @include md {
    height: 35vh;
  }

  @include xl {
    height: 110vh;
  }
}
.powers {
  background-color: $maroon;
  color: $beige;
}

ul {
  padding-left: 5%;
  padding-top: 2.5%;
  list-style: none;
  li {
    padding-left: 2.5%;

    border-bottom: solid 1px white;

    h1 {
      @include sm {
        font-size: 45px;
      }
      @include md {
        font-size: 60px;
      }

      @include xl {
        font-size: 85px;
        margin-top: 20px;
        margin-bottom: 20px;
      }
    }
  }
}
</style>
