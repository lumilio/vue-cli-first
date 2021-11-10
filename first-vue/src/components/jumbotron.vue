<template>

  <div class="bg-dark d-flex justify-content-center align-items-center container-fluid">
      <obj1/>
  </div>
  


</template>

<script>

import obj1 from './titolo.vue'

export default {
  name: 'HelloWorld',
  components: {
    /* HelloWorld */
    obj1,

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container-fluid{
    height: 500px;
}
</style>