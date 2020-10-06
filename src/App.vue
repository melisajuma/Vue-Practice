<template>
  <div id="app">
    <h1> {{ newTitle() }} </h1>
    <p> {{ newTitle() }} - <a v-bind:href="link">Google</a></p>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {},
  data(){
    return {
      title:"First title",
      link:'http://google.com'

    };
  },
  methods:{
    newTitle(){
      return this.title;
    }
  }
}
</script>

<style>

</style>
