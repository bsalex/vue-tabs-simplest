<template>
  <tabs>
    <tab>Test</tab>
  </tabs>
</template>

<script>
import { Tabs, Tab } from 'uiv'

export default {
  name: 'headerpanel',
  data() {
    return {

    }
  },
  components: {
    'tabs': Tabs,
    'tab': Tab
  }
}
</script>
