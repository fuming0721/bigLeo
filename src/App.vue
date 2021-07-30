<template>
  <div class="login-container">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="stylus">
*
  padding: 0;
  margin: 0;

.login-container
  display flex
  align-items center
  justify-content center
  position fixed
  width 100vw
  height 100vh
  margin 0 auto
  background url("http://www.17sucai.com/preview/242158/2015-01-10/%E7%99%BB%E5%BD%95/images/cloud.jpg") 0 bottom repeat-x #049ec4
  animation animate-cloud 10s linear infinite

@keyframes animate-cloud
  from
    background-position 0 100%
  to
    background-position 600px 100%
</style>
