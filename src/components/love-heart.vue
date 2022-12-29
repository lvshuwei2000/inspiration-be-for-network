<template>
  <div class="heart">
	<div class="love" v-for="item in 100" :style="{'--d':(item*-1)*0.5}">
		<div class="love-leng">
			<div class="love-cro">
				<div class="love-text">吕先生爱着高女士</div>
			</div>
		</div>
	</div>
  </div>
</template>

<script>
export default {
  name: 'love-heart',
  data() {
	  return {
		  
	  }
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	@import "./love.css"
</style>
