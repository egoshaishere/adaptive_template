<template>
  <div class="wrapper_templ">
    <headr /> 
    <cont />
    <foot />
  </div>
</template>

<script>
import Head from './header/Head'
import Cont from './content/Content'
import Foot from './footer/Foot'

export default {
  name: 'AdaptiveTampl',
  components: {
    headr: Head,
    cont: Cont,
    foot: Foot
  }

}
</script>

<style>


</style>