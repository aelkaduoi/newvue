<template>
  <div class="container">
    <div class="row">
      <div class="col-6">
      </div>
      <div class="col-6 align-self-center">
        <h1> vakantiekiezer</h1>
      </div>
    </div>

    <VacationPicker />
  </div>
</template>

<script>
import VacationPicker from './components/VacationPicker.vue'

export default {
  name: 'App',
  components: {
    VacationPicker
  }
}
</script>
