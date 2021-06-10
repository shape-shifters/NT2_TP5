<template>
    <div id="navigator">
			<button id="reset" @click="reset()"> {{ restartButton }}</button>
			<span id="message"> {{ messageDisplay }}</span>

			<button id="easy" @click="easy()" :class="{'selected': !isHard}">easy</button>
			<button id="hard" @click="hard()" :class="{'selected': isHard}">hard</button>
		</div>
</template>

<script>

  export default  {
    name: 'navigator',
    props: ['reset','easy','hard','restartButton','messageDisplay','isHard'],
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
  .navigator {

  }
</style>
