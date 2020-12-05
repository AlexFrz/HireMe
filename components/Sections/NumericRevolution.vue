<template>
  <section class="revolution">
    <div class="thenumericrevolution">
      <h2 class="first">The <span>Numeric Revolution</span> knocks.</h2>

      <h2 class="second">
        Traditional businesses <br />
        have two choices:
      </h2>
      <div class="makeachoice">
        <div class="firstchoice">
          <button>EVOLVE</button>
        </div>
        <div class="secondchoice">
          <button>DIE</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.revolution {
  background: linear-gradient(
    180deg,
    rgba(159, 11, 13, 1) 0%,
    rgba(83, 185, 198, 1) 10%,
    rgba(65, 144, 154, 1) 50%,
    rgba(83, 185, 198, 1) 100%
  );
  color: $beige;

  @include sm {
    height: 110vh;
  }

  @include md {
    height: 65vh;
  }
  @include xl {
    height: 100vh;
  }
}

h2 {
  @include sm {
    font-size: 60px;
  }
}

.thenumericrevolution {
  @include sm {
    padding-top: 100px;
  }
  @include md {
    justify-content: center;
    text-align: center;
  }
  padding-inline: 5%;
  padding-top: 10%;
  span {
    color: #befbff;
  }

  .second {
    padding-top: 7%;
  }
}

.makeachoice {
  @include sm {
    margin: auto;
    padding-top: 10%;
  }
  @include md {
    display: flex;
    padding: 7.5%;
    justify-content: space-evenly;
  }
}

button {
  color: #53b9c6;
  background-color: $beige;
  font-family: 'Zona Black';
  font-size: 60px;
  @include sm {
    width: 90vw;
    margin-bottom: 10px;
  }
  @include md {
    width: 300px;
    height: 125px;
    margin: 10px;
  }
}
</style>
