<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>{{name}}</div>
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },

  setup () {
    const name = ref('张三')

    return {
      name
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
h3
  margin 40px 0 0

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px

a
  color #42b983
</style>
