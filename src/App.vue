<template>
  <CreatePost/>
  <PostList/>
</template>

<script>
import PostList from './components/PostList.vue'
import CreatePost from './components/CreatePost.vue'

export default {
  name: 'App',
  components: {
   PostList,
   CreatePost,
  },
  data() {
    return {}
  },
  methods: {},
}
</script>

<style scoped></style>
