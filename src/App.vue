<template>
  <div id="app">
   <navigation/>
      <router-view/>
  
  </div>
</template>

<script>
import navigation from '@/components/NavigationBar.vue'
export default {
  
  components: {
    navigation,
  }
}


</script>

