<template>
  <div id="app">
    <input type ="text" v-on:input="changeTitle">
    <h1> {{ newTitle() }} </h1>
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
    newTitle(){
      return "new Title!";
    }
  }
}
</script>

<style>

</style>
