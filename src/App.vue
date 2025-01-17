<template>
  <button @click="showPopup = true" >Show Popup</button>
 <Popup v-show="showPopup" @close="closePopup"/>
</template>

<script>
import Popup from './components/Popup.vue'

export default {
  name: 'App',
  components : {
    Popup,
  },
  data () {
    return {
      showPopup: false,
    }
  },
  methods: {
    closePopup (name) {
      this.showPopup = false
      console.log(name)
    }
  }
  
}
</script>

<style scoped>


</style>
