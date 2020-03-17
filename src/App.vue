<template>
  <div id="app">
    <Header title="JTODE"/>
    <div class="box">
      <todo></todo>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import todo from './components/todo.vue'
import Header from './components/header.vue'
import Footer from './components/footer.vue'
export default {
  name: 'App',
  components: {
    todo,
    Header,
    Footer
  }
}
</script>

<style lang="stylus" scoped>
  #app
    position absolute
    left 0
    right 0
    top 0
    bottom 0
    #cover
        position absolute
        left 0
        right 0
        top 0
        bottom 0   
        background-color #999 
        opacity 0.2
        z-index -1
  
.box
    width:600px;
    margin:0 auto
    display flex

</style>
