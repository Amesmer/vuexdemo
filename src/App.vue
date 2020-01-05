<template>
  <div>
    <my-addtion></my-addtion>
    <p>------------------------------</p>
    <my-subtraction></my-subtraction>
  </div>
</template>

<script>
import Addtion from './components/Addition'
import Subtraction from './components/Subtration'
export default {
  data () {
    return {}
  },
  components: {
    'my-addtion': Addtion,
    'my-subtraction': Subtraction
  }
}
</script>
<style lang="less" scoped>
</style>
