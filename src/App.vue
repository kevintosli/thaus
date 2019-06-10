<template>
  <thaus-app>
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </thaus-app>
</template>

<style lang="scss">
// @import url("https://fonts.googleapis.com/css?family=Rubik:400,500,700&display=swap");
@import url('https://fonts.googleapis.com/css?family=Overpass:300,400,600,700&display=swap');

thaus-app {
  background-color: var(--color-bg-primary);
  display: block;
}
</style>
