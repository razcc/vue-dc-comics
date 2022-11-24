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
.NavCont{
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	margin-left: 20px;
}
ul{
    display: flex;
	height: 100%;
	justify-content: center;
	align-items: center;
}
li {
	text-transform: uppercase;
    list-style-type: none;
    margin: 0 10px;  
	height: 100%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
}
li:hover{
	border-bottom: 4px solid blue;
}

</style>
