<template>
    <div>
   <h2 class="signup">Signup {{count}}</h2>
     <button @click="count++">Count is: {{ count }}</button>
    </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>


