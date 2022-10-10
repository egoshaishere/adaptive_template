<template>
  <div id="app">
    <AdaptiveTempl />
  </div>
</template>

<script>
import AdaptiveTempl from './components/AdaptiveTempl.vue'

export default {
  name: 'App',
  components: {
    AdaptiveTempl
  }
}
</script>

<style>
@import './styles/style.css';


#app {
  /* background-color: #ebd5b3;  https://encycolorpedia.ru/f2eecb*/
  background-color: #f2eecb;
  height: 100%;

}
body {
  margin: 0;
}

html,
body {
	height: 100%;
}
</style>
