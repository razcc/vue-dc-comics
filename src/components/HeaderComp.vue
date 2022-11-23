<template>
	<div class="contHeader">
		<div id="container">
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
.contHeader {
	background-color: white;
	padding: 10px;
}
#container{
  display: flex;
	justify-content: space-between;
	align-items: center;
  width: 70%;
  margin: auto;

}
</style>
