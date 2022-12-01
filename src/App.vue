<template>
  <div id="app">
    <InputNumberRange
        v-model="value"
    ></InputNumberRange>
    <h2>value:{{this.value}}</h2>
  </div>
</template>

<script>
import InputNumberRange from 'input-number-range'
// import InputNumberRange from '../../lib/input-number-range/lib/InputNumberRange';
export default {
  name: 'App',
  components: {
    InputNumberRange
  },
  data(){
    return{
      value:[]
    }
  },
  methods:{

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing
