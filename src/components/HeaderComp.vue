<template>
	<div class="contHeader">
		<div class="container">
			<LogoComp />
			<NavComp />
		</div>
	</div>
</template>

<script>
import LogoComp from "./ComponetiHeader/LogoComp";
import NavComp from "./ComponetiHeader/NavComp.vue";

export default {
	name: "HeaderComp",
	components: {
		LogoComp,
		NavComp,
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
	display: flex;
	justify-content: space-between;
	align-items: center;
	width: 70%;
	margin: auto;
	
}
.contHeader {
	background-color: white;	
	padding: 20px 0px 0px 0px;
}

</style>
