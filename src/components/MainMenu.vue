<template>
	<div id="MainMenu">
        <div class="container">
            <ul>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="Comics">
                    <span>digital comics</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-merchandise.png" alt="Comics">
                    <span>dc merchandise</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="Comics">
                    <span>subscription</span>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="Comics">
                    <span>comic shop locator</span>
                </li>
                <li>
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="Comics">
                    <span>dc power visa</span>
                </li>
            </ul>
        </div>
    </div>
</template>


<script>


export default {
	name: "MainMenu",
};
</script>
<style scoped lang='scss'>
#MainMenu{
    height: 20vh;
    width: 100%;
    background-color: rgba(2, 130, 249, 1);
    position: relative;
    z-index: 1;
}
.container{
    width: 60%;
    margin: auto;
    height: 100%;
}
ul{
    display: flex;
    justify-content: space-around;
    align-items: center;
    list-style: none;
    height: 100%;
    color: white;
}
li{
    display: flex;
    align-items: center;
    height: 30%;
    text-transform: uppercase;
    transition: all 2s;
    
}
img{
    
    height: 100%;
    margin: 0 10px;
    transition: all 2s;

}


li:hover{
    transform: scale(1.2); 
    cursor: pointer;
}
</style>