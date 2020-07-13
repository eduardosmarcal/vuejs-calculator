<template>
  <div class="display">
    {{ value }}
  </div>
</template>

<script>
export default {
  props: {
    value: {
      type: String,
      required: true
    }
  }
}
</script>

<style>
.display {
  background-color: #0004;
  font-size: 2.1em;
  grid-column: span 4;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding: 30px 20px;
  overflow: hidden;
}
</style>