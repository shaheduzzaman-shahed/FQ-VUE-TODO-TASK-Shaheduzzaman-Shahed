<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" height="250" width="250">
    <HelloWorld msg="Sayburg Frontend Dev Test"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
