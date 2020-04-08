<template>
  <AppCard v-bind="$attrs">
    <div>Player card content</div>
  </AppCard>
</template>

<script>
import AppCard from "./AppCard";

export default {
  name: "PlayerCard",
  components: {
    AppCard
  },
  inheritAttrs: false
}
</script>