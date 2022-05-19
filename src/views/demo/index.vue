<template>
  <div>
    <DemoLayout>
      <template slot="header"><Directive /></template>
      <template slot="body">222</template>
      <template slot="footer">333</template>
    </DemoLayout>
  </div>
</template>

<script>
import DemoLayout from '@/layout/demo/index.vue'
import Directive from './directive.vue'

export default {
  components: {
    DemoLayout,
    Directive
  }
}

</script>
