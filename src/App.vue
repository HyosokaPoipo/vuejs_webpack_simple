<template>
  <div id="app">
    <img src="./assets/boruto_kage.png">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li><a href="https://www.youtube.com/channel/UCXu-D19AiIJZptbg8Z549xg" target="_blank">Youtube</a></li>
      <li><a href="http://dimensitutupbotol.blogspot.co.id/" target="_blank">Blog</a></li>
      <li><a href="https://www.facebook.com/Hyosoka.Poipo" target="_blank">Facebook</a></li>
      <li><a href="https://twitter.com/hyosokapoipo" target="_blank">Twitter</a></li>
      <li><a href="https://github.com/HyosokaPoipo/vuejs_webpack_simple" target="_blank">Github</a></li>
    </ul>
    <h2>Popular Videos</h2>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=2KYNQmszbJ8" target="_blank">Meet Grandpa</a></li>
      <li><a href="https://www.youtube.com/watch?v=70IcY0YZMqI" target="_blank">Visit Ichiraku Ramen</a></li>
      <li><a href="https://www.youtube.com/watch?v=Jbi54W6WMeM" target="_blank">Himawari's Byakugan</a></li>
      <li><a href="https://www.youtube.com/watch?v=I1OTkS3KZK0" target="_blank">Naruto's Prank</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Boruto Lovers Page hehe :D'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
