<template>
	<div class="card">
		<img :src="dettagliCard.thumb" alt="" />
		<div class="cardTitle">
			<h3>{{ dettagliCard.series }}</h3>
		</div>
	</div>
</template>


<script>
export default {
	name: "CardComp",
	props: {
		dettagliCard: Object,
	},
};
</script>

<style scoped lang='scss'>
.card {
	width: calc(100% / 6 - 30px);
	height: 100%;
	// !Da chiedere perchè height funziona
	padding: 0 5px 0;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
img{
	width: 100%;
}
h3 {
	color: white;
}
.cardTitle {
	width: 100%;
	margin: 20px 0 40px 0;
}
</style>