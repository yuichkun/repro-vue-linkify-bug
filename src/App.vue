<template>
  <div id="app">
    <HelloWorld :msg="msg"/>
    <button @click="changeText">Change text</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data() {
    return {
      msg: "Initial Text https://google.com"
    }
  },
  methods: {
    changeText: function() {
      this.msg = "Changed Text https://example.com"
    }
  },
  components: {
    HelloWorld
  }
}
</script>