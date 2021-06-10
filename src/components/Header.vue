<template>
    <div id="header" :style="{backgroundColor: color}">
      <h1>The Great <br>
        <span id="colorDisplay">{{pickedColor}}</span>
        <br>
        Guessing Game</h1>
		</div>
</template>

<script lang="js">

  export default  {
    name: 'header',
    props: ['color','pickedColor'],
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="css">
  .header {

  }
</style>
