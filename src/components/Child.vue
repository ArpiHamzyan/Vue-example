<template>
   <div>Child Component</div>
</template>
    
<script>
 export default {
      name: 'Child',
      beforeCreate() {
        console.log('Childe beforeCreate()')
      },
      created () {
        console.log('Childe created ()')
      },
      beforeMount() {
        console.log('Childe beforeMount()')
      },
      mounted(){
        console.log('Childe mounted()')
      },
      beforeUpdate() {
        console.log('Childe beforeUpdate()')
      },
      updated() {
        console.log('Childe updated()')
      },
      beforeUnmount(){
        console.log('Childe beforeUnmount()')
      },
      unmounted(){
        console.log('Childe unmounted()')
      },

};
</script>
    
<style scoped>
    
</style>
    