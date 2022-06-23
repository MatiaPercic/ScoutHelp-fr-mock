<template>
  <div class="home">
    <HelloWorld msg="Ovo je mock alikacije ScoutHelp"/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
