<template>
  <div>
    <button @click="sweetalert">click me</button>
    <div class="btn-group"
         role="group"
         aria-label="...">
      <button type="button"
              class="btn btn-default">Left</button>
      <button type="button"
              class="btn btn-default">Middle</button>
      <button type="button"
              class="btn btn-default">Right</button>
    </div>
  </div>
</template>

<script>
$(function () {
  alert(123);
});
export default {
  name: 'home',
  methods: {
    sweetalert (e) {
      this.$swal('this is sweetalert2')
    }
  }
}
</script>

<style scoped>
</style>

