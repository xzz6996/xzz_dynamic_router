<template>
  <div class="home">
    <HelloWorld msg="Welcome to Home"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  created(){
    console.log(this.$router)
  }
}
</script>
