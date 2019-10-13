<template>
    <div id="eclipse">
    <Title />
    </div>
</template>
<script>
import Title from "./Title";
export default {
    name: "titleContainer",  
    components: {
        Title
    }  
}
</script>
<style scoped>
#eclipse , div {
    background: url("../../assets/eclipse.jpg") no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    width: 100%;
    height: 100%;
    display: flex;
    align-content: center;
    padding-top: 10%;
    padding-bottom: 50%;
}

@media only screen and (min-width: 900px) {
    #eclipse , div {
        background: url("../../assets/eclipse.jpg") no-repeat fixed;
        background-position: center top;
        padding-top: 5%;
        height: 100%;
        padding-bottom: 10%;
    }
}
</style>