<template>
  <div class="home">
    <FieldAddTask />

    <list-tasks
      v-if="$store.state.tasks.length"
    />

    <no-tasks v-else />

  </div>
</template>

<script>
import FieldAddTask from '@/components/Todo/FieldAddTask'

export default {
  name: 'Home',
  components: {
    FieldAddTask,
    'list-tasks': require('@/components/Todo/ListTasks.vue').default,
    'no-tasks': require('@/components/Todo/NoTasks.vue').default
  },
  
}
</script>

