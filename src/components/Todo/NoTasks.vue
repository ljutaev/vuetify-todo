<template>
 <div 
    class="text-h5 primary--text no-tasks"
  >
    <v-icon
      size="100"
      class="primary"
    >
      mdi-check
    </v-icon>
    No tasks
  </div>
</template>

<script>
  export default {
  }
</script>

<style lang="sass">
  .no-tasks
    position: absolute
    left: 50%
    top: 50%
    transform: translate(-50%, -50%)
</style>