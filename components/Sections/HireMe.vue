<template>
  <section class="hire-me">
    <div class="text">
      <h1>We can create</h1>
      <h1>Big things</h1>
      <h1 class="maroon">Together.</h1>
      <button>Hire me</button>
      <div class="socialmedia">
        <img src="~/assets/images/insta.png" alt="" />
        <img src="~/assets/images/linked.png" alt="" />
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
section {
  @include sm {
    height: 70vh;
  }
  height: 130vh;
  justify-items: center;
}

.text {
  width: 75vw;
  justify-content: center;
  align-content: center;
  margin: auto;
  padding-top: 7.5%;
  text-align: center;
}

.maroon {
  color: $maroon;
}

button {
  @include sm {
    width: 70vw;
    height: 20vw;
    font-size: 60px;
  }
  width: 65vw;
  height: 25vh;
  background-color: $maroon;
  color: white;
  font-family: 'Zona Black';
  font-size: 160px;
  margin-top: 7%;
}

.socialmedia {
  width: 40%;
  display: flex;
  margin: auto;
  img {
    width: 35%;
    padding-top: 20%;
  }
}
</style>
