<template>
<h1 style="font-size: 100px" v-bind:class="{data: counter < 0}">{{ counter }}</h1>
<button style="margin-right: 10px" v-on:click="counter++" type="button" class="btn btn-outline-primary">+</button>
<button v-on:click="counter--" type="button" class="btn btn-outline-danger">-</button>
</template>

<script>
export default {
  name: 'MainCounter',
  data () {
    return {
      counter: 0
    }
  }
}
</script>

<style scoped>
.data {
    color: rgb(238, 105, 105)
}
</style>
