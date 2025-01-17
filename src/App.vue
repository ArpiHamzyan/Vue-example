<template>
 <!-- <Greet name="Bruce" heroName="Batman"/>
 <Greet name="Clark" heroName="Superman"/>
 <Greet name="Diana" heroName="Wonde Women"/>
 <Greet :name="name" :heroName="channel"/> -->

 <Article id="my-article" title="Article Title" :likes="50" :isPublished="true"/>
</template>

<script>
//import Greet from './components/Greet.vue'
import Article from './components/Article.vue'

export default {
  name: 'App',
  components : {
    //Greet,
    Article,
  },
  data () {
    return {
      name: 'Vishwas',
      channel: 'Codevolution'
    }
  }
  
}
</script>

<style scoped>


</style>
