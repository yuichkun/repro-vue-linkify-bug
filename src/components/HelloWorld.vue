<template>
  <div>
    <div>
      <h2>Without vue-linkify</h2>
      This gets changed: {{ msg }}
    </div>
    <div v-linkified>
      <h2>With vue-linkify</h2>
      This does not get changed: {{ msg }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
