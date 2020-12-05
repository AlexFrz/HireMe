<template>
  <div class="theheader">
    <div class="logo"><h4>Logo</h4></div>
    <button>Hire Me</button>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.theheader {
  display: flex;
  width: 100%;
  justify-content: space-between;
  padding: 30px;
}
button {
  background-color: $maroon;
  color: white;
  font-family: 'Zona Black';
  @include sm {
    margin-top: -15px;
    margin-right: -10px;
    width: 50vw;
    height: 10vh;
    font-size: 30px;
  }
  @include md {
    width: 30vw;
    height: 10vh;
  }
  @include lg {
    width: 200px;
    height: 75px;
    font-size: 30px;
  }
}
</style>
