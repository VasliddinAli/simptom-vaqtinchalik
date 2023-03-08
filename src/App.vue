<template>
  <HelloWorld />
  <StyleCss />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import StyleCss from './components/style/style.css';

export default {
  name: 'App',
  components: {
    HelloWorld,
    StyleCss
  }
}
</script>