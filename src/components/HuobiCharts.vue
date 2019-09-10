<template>
  <div class="page">
        <h3>引用了子集  {{tit}}</h3>

        <h4>{{txt}}</h4>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  name:'huobiCharts',
  props:{
    txt:String
  },

  data() {
    return {
        tit:'子集标题是  ABC',
        oppo:'oppo!'
        
    }
  },
  
  
 
}
</script>

<style scoped lang="stylus">
</style>
