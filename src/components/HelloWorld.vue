<template>
  <div>
    <div>
      This gets changed: {{ msg }}
    </div>
    <div v-linkified>
      This does not: {{ msg }}
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
