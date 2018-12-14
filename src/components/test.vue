<template>
	
	<div id="components-demo">
	  <button v-on:click="count++">You clicked me {{ count }} times.</button>
	</div>
</template>

<script>
	export default {
		name: "components-demo",
		data: function () {
			return {
			  count: 0
			}
		},		
	}
</script>

<style>

</style>
