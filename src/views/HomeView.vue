<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  <p>
    1
  2
3
  </p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  data() {
    return {
      name: 'jk',
      age: '1',
      sex: '男'
    }
  },
  components: {
    HelloWorld
  }
}
</script>
