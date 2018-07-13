<template>
  <div id="app">
    <calendar-week />
    <calendar-entry />
  </div>
</template>

<script>
import CalendarEntry from './components/CalendarEntry.vue'
import CalendarWeek from './components/CalendarWeek.vue'

export default {
  name: 'App',
  components: {
    CalendarWeek,
    CalendarEntry
  },
}
</script>

<style lang="scss">
  html, body {
    height: 100%;
  }
  
  #app {

  }

  #calendar-week {

  }

  #calendar-entry {

  }
</style>
