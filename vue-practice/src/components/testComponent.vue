// UI goes here
<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>

// Component/App logic in Script tag
<script>
export default {
  name: "testComponent",
  props: {
    message: String
  }
};
</script>