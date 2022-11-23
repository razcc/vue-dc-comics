<template>
	<div id="ContentCont">
        <div class="container">
             <h2>--&gt; Content goes here &lt;-- </h2>
        </div>
       
    </div>
</template>


<script>

export default {
	name: "ContentComp",

};
</script>

<style scoped lang='scss'>
#ContentCont{
    width: 100%;
    height: 20vh;
    display: flex;
    align-items: center;
}

.container{
    width: 70%;
    height: 20%;
    margin: auto;
    display: flex;
    align-items: center;
}
h2{
    color: white;
}

</style>