<template>
  <div class="container">
    <div>
      <header-widget></header-widget>
    </div>
    <div>中间</div>
    <div>底部</div>
  </div>
</template>

<script>
import headerWidget from '@/components/header.vue'
export default {
  components: { headerWidget },
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
