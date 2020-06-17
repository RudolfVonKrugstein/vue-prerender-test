<template>
  <div class="home" data-view>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import { Component } from 'vue-property-decorator'
import Vue from "vue";

@Component({
  components: {
    HelloWorld
  }
})
export default class App extends Vue {
}
</script>
