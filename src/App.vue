<template>
  <div id="app">
    <div id="slider_wrapper">
      <div id="slider">
        <div class="slide_one slie">
          <img src="./assets/boruto_kage.png">
        </div>
        <!-- <div class="slide_two slie">
          <img src="./assets/boruto_rasenggan.png">
        </div>
        <div class="slide_three slie">
          <img src="./assets/boruto_running.png">
        </div>
        <div class="slide_four slie">
          <img src="./assets/boruto_miniatur.png">
        </div> -->
      </div>
    </div>
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

#slider_wrapper {
  overflow: hidden;

}

#slider {
  position: relative;
   -webkit-animation-name: slide_animation;
   -webkit-animation-duration:9s;
   -webkit-animation-iteration-count:infinite;
   -webkit-animation-direction:alternate;
   -webkit-animation-play-state: running;
}

.slie {
  width:500px;
  height: 370px;
  position:relative;
  float:left;
  overflow:hidden;
}

@-webkit-keyframes slide_animation {
  0% {left:0px;}
  10% {left:100px;}
  20% {left:200px;}
  30% {left:300px;}
  40% {left:400px;}
  50% {left:500px;}
  60% {left:600px;}
  70% {left:700px;}
  80% {left:800px;}
  90% {left:900px;}
  100% {left:1000px;}
}
</style>
