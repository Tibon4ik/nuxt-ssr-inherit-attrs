<template>
  <div class="app-card">
    <div>{{ appCardProp }}</div>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "AppCard",
  props: {
    appCardProp: {}
  }
}
</script>