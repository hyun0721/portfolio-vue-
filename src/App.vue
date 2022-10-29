<template>
  <div class="layout" id="app">
    <NavigateBar></NavigateBar>
    <HomeArea></HomeArea>
    <AboutArea></AboutArea>
    <Skills></Skills>
    <Contact></Contact>
  </div>
</template>

<script>

import NavigateBar    from './components/home/Navigate.vue';
import Home           from './components/home/Home.vue';
import About          from './components/home/About.vue';
import Skills         from './components/home/Skills.vue';
import Contact        from './components/home/Contact.vue';

export default {
  name: 'app',

  created: function(){
    console.log('Start ...');
  },
  
  components: {
    'NavigateBar' : NavigateBar,
    'HomeArea'    : Home,
    'AboutArea'   : About,
    'Skills'      : Skills,
    'Contact'     : Contact
  }
}
</script>

<style>

@import "./assets/css/global.css";

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
