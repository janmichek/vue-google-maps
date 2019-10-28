<template>
  <input
    ref="input"
    v-bind="$attrs"
    v-on="$listeners"
    />
</template>

<script>
export default ((x) => x.default || x)(require('../components-implementation/autocomplete'))
</script>
