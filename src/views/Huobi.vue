<template>
  <div class="page">
      <h2>虚拟货币实时行情</h2>

      <HChars txt="htjs"/>
  </div>
</template>



<script type="text/ecmascript-6">

import HChars from '@/components/HuobiCharts.vue'

export default {
  data() {
    return {
        dataObj:{

        }
    }
  },
  components: {
    HChars
  }
}
</script>

<style scoped lang="stylus">
</style>
