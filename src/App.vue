<script >
import axios from 'axios'
export default {
  data() {
    return {
    }
  },
  methods: {
    clickButton() {
      axios.get('/test').then((e) => {console.log(e)}).catch((err) => {})
    }

  }
}
</script>

<template>
  <button @click="clickButton" >click</button>
</template>

<style scoped>

</style>
