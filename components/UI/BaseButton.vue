<template>
  <button><slot></slot></button>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
button {
  background-color: $maroon;
  color: white;
  font-family: 'Zona Black';

  @include sm {
    @include sm {
      width: 70vw;
      height: 20vw;
      font-size: 60px;
    }
  }

  @include xl {
    width: 200px;
    height: 75px;
    font-size: 30px;
  }
}
</style>
