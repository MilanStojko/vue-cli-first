<template>
  <div>
    <img src="../assets/Aminem_Amogus_Eminem.png" alt="">
    <Title msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import Title from './Title.vue'

export default {
  name: "Hero",
  components: {
    Title
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">
h1
  color: red
  font-size: 90px
h3 
  margin: 40px 0 0
ul 
  list-style-type: none
  padding: 0
li 
  display: inline-block
  margin: 0 10px
a 
  color: #42b983
</style>
