<style lang="style" scope>
.msg {
  font-size: 30px;
}
</style>

<template>
  <div class="msg">
    {{ msg }}
  </div>
</template>>

<script>
export default {
  name: "{template}",
  data () {
    msg: 'hello!'
  },
  created () {
    console.log('created')
  },
  mounted () {
    console.log('mounted')
  },
  beforeDestroy () {
    console.log('beforeDestroy')
  }
}
</script>