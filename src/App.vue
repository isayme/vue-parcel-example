<template>
  <div id="app">
    Time: {{ now }}
  </div>
</template>

<script>
export default {
  computed: {
    now () {
      return new Date().toISOString()
    }
  }
}
</script>