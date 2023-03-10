<script >
import { RouterLink, RouterView } from 'vue-router'
import Signup from './components/Signup.vue'
import Home from './components/Home.vue'
export default{
    name:'app',
    components:{
        Signup,
        Home
    },
}
</script>

<template>
  <RouterView/>
  <!-- <Signup/> -->

</template>

<style scoped>

</style>
