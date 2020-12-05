<template>
  <section class="projects">
    <div class="projects__banner">
      <h2>Some of my projects</h2>
    </div>
    <div class="project">
      <div class="card">
        <div
          class="card__bg"
          :style="{
            background: `url(${backgroundUrl}) center / cover no-repeat`,
          }"
        ></div>
      </div>
      <div class="textxl">
        <div class="title"><h3>THEIRSTORIES</h3></div>
        <div class="description">
          <h5>
            THEIRSTORIES is a non-profit organisation of journalists, travelers
            and philanthropists who go all around the world to meet those people
            that have stories to share.
          </h5>

          <h5>
            They write articles about them, photos and videos to witness how
            life is abroad.
          </h5>

          <h5>
            On this website, good-hearted visitors can donate to those people
            which, often, need it.
          </h5>

          <div class="website">
            <h5>www.theirstories.com</h5>
            <h5>Built with React & Firebase.</h5>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import backgroundUrl from '@/assets/images/theirstories_optimized.png'

export default {
  data() {
    return {
      backgroundUrl,
    }
  },
}
</script>

<style scoped lang="scss">
section {
  @include sm {
    height: 300vh;
  }
  @include xl {
    height: 130vh;
  }
}
.projects__banner {
  width: 100%;

  background: $maroon;
  color: $beige;
  text-align: center;
  @include sm {
    height: 60px;
  }
  @include md {
    height: 100px;
  }
  @include xl {
    height: 150px;
  }
}

h2 {
  @include sm {
    font-size: 30px;
  }
  @include md {
    font-size: 60px;
  }
  padding-top: 2.5%;
}

h5 {
  margin: 4%;
}

.project {
  @include sm {
    height: 300vh;
    .card {
      margin: 2.5%;
      margin-left: 5%;
      border-radius: 15px;
      box-shadow: 5px 5px 20px -5px rgba(0, 0, 0, 0.3);
      cursor: pointer;
      display: inline-block;
      box-sizing: border-box;
      height: 80vh;
      overflow: hidden;
      perspective: 500px;
      position: relative;
      width: 90vw;
      text-align: center;
      opacity: 0.9;
    }
    .card__bg {
      bottom: -50px;
      left: -50px;
      position: absolute;
      right: -50px;
      top: 0px;
      z-index: 0;
      transition: 0.5s;
    }
    .card__bg:hover {
      transform: scale(1.08);
      opacity: 1;
    }
    h3 {
      font-size: 40px;
      text-align: center;
      padding-top: 5%;
    }
    h5 {
      text-align: center;
    }

    .website {
      padding-top: 10px;
      line-height: 20px;
      color: $maroon;
    }
  }

  @include xl {
    display: flex;
    height: 95vh;
    .card {
      margin: 2.5%;
      margin-left: 5%;
      border-radius: 15px;
      box-shadow: 5px 5px 20px -5px rgba(0, 0, 0, 0.3);
      cursor: pointer;
      display: inline-block;
      box-sizing: border-box;
      height: 95vh;
      overflow: hidden;
      perspective: 500px;
      position: relative;
      width: 45vw;
      text-align: center;
      opacity: 0.9;
    }
    .card__bg {
      bottom: -50px;
      left: -50px;
      position: absolute;
      right: -50px;
      top: 0px;
      z-index: 0;
      transition: 0.5s;
    }

    .card__bg:hover {
      transform: scale(1.08);
      opacity: 1;
    }

    .textxl {
      width: 50vw;
      text-align: center;
      justify-content: center;
      padding-top: 2.5%;
    }
    .textsm {
      display: none;
    }

    .title {
      padding: 5%;
    }

    .description {
      margin-inline: 7.5%;
      width: 40vw;
    }

    .website {
      color: $maroon;
      padding-top: 17.5%;

      h5 {
        margin-bottom: -3%;
      }
    }
  }
}
</style>
