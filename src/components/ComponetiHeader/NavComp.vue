<template>
	<div class="NavCont">
		<ul>
			<li>characters</li>
			<li>comics</li>
			<li>movies</li>
			<li>tv</li>
			<li>games</li>
			<li>collectibles</li>
			<li>fans</li>
			<li>videos</li>
			<li>news</li>
			<li>shop</li>
		</ul>
	</div>
</template>

<script>
export default {
	name: "NavComp",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

ul{
    display: flex;



}
li {
	text-transform: uppercase;
    list-style-type: none;
    margin: 0 10px;
   
}

</style>
