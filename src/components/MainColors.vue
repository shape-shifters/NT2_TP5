<template>
    <div id="container">
			<Square 
				class="square" 
        :index="index"
				:fmensajes="fmensajes"
				:mensajes="mensajes"
				:square="square"
				:fsquare="fsquare"
				:set-all-colors-to="setAllColorsTo"
				:picked-color="pickedColor"
				v-for="(square,index) in squares"
				:key="index"
			/>
		</div>
</template>

<script lang="js">

  import Square from './Square'
  export default  {
    name: 'main-colors',
    props: [
      'squares','fsquare',
      'mensajes','fmensajes',
      'pickedColor','setAllColorsTo'
    ],
    components: {
      Square
    },
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
  .main-colors {

  }
</style>
