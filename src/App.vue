<template>
  <div id="app">
    <input type ="text" v-on:input="changeTitle">
    <h1> {{title}} </h1>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {},
  data(){
    return {
      title:"First title"

    };
  },
  methods:{
    changeTitle(){
      this.title = event.target.value;
    }
  }
}
</script>

<style>

</style>
