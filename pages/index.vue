<template>
  <div class="container">
    <PlayerCard app-card-prop="AppCard prop value" />
  </div>
</template>

<script>
import PlayerCard from "@/components/PlayerCard";

export default {
  components: {
    PlayerCard
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
