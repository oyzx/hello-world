<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>count: {{msg}}</div>
  </div>
</template>

<script>
import store from '@/store'

export default {
  name: "About",
  store,
  data () {
    return {
      msg: store.state.count
    }
  }
}
</script>
