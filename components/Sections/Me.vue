<template>
  <section class="me">
    <div class="description">
      <h3>I am <span>Alex</span>.</h3>
      <h3>A french freelance <span>UI/UX Designer & Developer</span>.</h3>
      <h3>Passionate about passion.</h3>
      <h3>Helping people to live their own truth.</h3>
      <h3>Cristalyzing ideas.</h3>
      <img src="~/assets/images/layout.png" class="portrait" />
    </div>

    <div class="stack">
      <h3><span>JAMSTACK:</span></h3>
      <h3>React.js && Vue.js</h3>
      <h3>API's/Headless CMS's</h3>
      <h3>Shopify/Storyblok</h3>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.me {
  background: linear-gradient(
    180deg,
    rgba(159, 11, 13, 1) 0%,
    rgba(30, 30, 30, 1) 100%
  );

  @include sm {
    height: 150vh;
  }

  @include xl {
    height: 110vh;
  }
}

.description {
  padding-top: 2.5%;
  padding-left: 5%;
  width: 90vw;
  position: relative;
  @include sm {
    padding-top: 10%;
    text-align: center;
  }
  @include lg {
    text-align: left;
  }
}

.stack {
  @include sm {
    padding-top: 10%;
    text-align: center;
  }
  @include lg {
    padding-top: 7.5%;
    padding-left: 5%;
  }
}

span {
  font-weight: 600;
}

h3 {
  font-family: 'Montserrat';
  font-weight: 300;
  font-size: 35px;
  color: white;
  padding-top: 2%;
  line-height: 37.5px;
}

.portrait {
  @include sm {
    width: 100vw;
    top: 0;
    margin-left: -40px;
  }
  @include xl {
    width: 45vw;
    position: absolute;
    right: -10%;
    top: 45%;
  }
}
</style>
