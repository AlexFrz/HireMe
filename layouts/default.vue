<template>
  <div>
    <Nuxt />
  </div>
</template>

<style lang="scss">
@font-face {
  font-family: 'Zona Black';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/ZonaBlack.ttf') format('truetype');
}

html {
  font-family: 'Zona Black', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  color: $black;
  overflow-x: hidden;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  overflow: hidden;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

section {
  width: 100vw;
  height: 100vh;
}

h1 {
  @include sm {
    font-size: 60px;
  }

  @include md {
    font-size: 90px;
  }

  @include xl {
    font-size: 100px;
  }
}

h2 {
  font-size: 70px;
}

h3 {
  font-size: 50px;
}

h4 {
  font-size: 30px;
}

h5 {
  font-size: 22px;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
