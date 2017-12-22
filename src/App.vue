<template>
  <div id="app">
    <classic></classic>
    <modern></modern>
  </div>
</template>

<script>
import {Classic, Modern} from './index.js'

export default {
  name: 'app',
  components: {
    Classic,
    Modern
  }
}
</script>
