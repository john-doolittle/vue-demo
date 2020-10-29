<template>
  <div>
    <h3>You clicked {{ count }} times</h3>
    <button v-on:click="count++">Click me</button>
  </div>
</template>

<script>
export default {
  name: 'CounterBtn',
  data: function () {
    return {
      count: 0
    }
  }
}
</script>