<template lang="html">
  <div>
    <client-only>
      <my-prism-editor :code="code" language="js"></my-prism-editor>
    </client-only>
  </div>
</template>

<script>
export default {
  data() {
    return {
      code: '// index\nconst x = 10; x++; x--;'
    }
  }
}
</script>

<style lang="css" scoped></style>
