<template>
  <div class="layout" id="app">
    <NavigateBar></NavigateBar>
    <HomeArea></HomeArea>
    <AboutArea></AboutArea>
  </div>
</template>

<script>

import NavigateBar    from './components/home/NavigateBar.vue';
import Home           from './components/home/Home.vue';
import About          from './components/home/About.vue';

export default {
  name: 'app',

  created: function(){
    console.log('Start ...');
    console.log('Test ...');
  },
  
  components: {
    'NavigateBar' : NavigateBar,
    'HomeArea'    : Home,
    'AboutArea'   : About
  }
}
</script>

<style>

body {
  width: 100%;
  height: 100%;
  margin: 0px;
}

.shadow {
  box-shadow: 5px 10px 10px rgba(0,0,0,0.03);
}

.layout {
  /* display: inline-flex;
  flex-direction: column; */
}

</style>
