<template>
  <div>
    <Main :propData='initData'/>
  </div>
</template>

<script>
import Main from './components/Main'
export default {
    data(){
      return {
        initData: 'hello 你好 world'
      }
    },
    components:{
      Main
    }
}
</script>

<style>

</style>