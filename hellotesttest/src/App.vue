<template class="bg">

  <div class="img1" style="margin-top: 30px;">
    
    <div>
    
    <router-view></router-view>
    </div>


  
    <div>
      <router-link to ="/basket">Go to Basket</router-link>
    </div>
    

  </div>
  
  
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {

  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #edeff1;
  margin-top: 60px;
}

</style>
