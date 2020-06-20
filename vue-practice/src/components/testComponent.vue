// UI goes here
<template>
  <div>
    <h1>{{ message }}</h1>
    <h2>This is pretty cool</h2>
    <button v-on:click="count++">I've been clicked {{ count }} times!</button>
  </div>
</template>

// Component/App logic in Script tag
<script>
export default {
  name: "testComponent",
  props: {
    message: String
  },
  data: function() {
    return {
      count: 0
    };
  }
};
</script>