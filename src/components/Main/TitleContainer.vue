<template>
    <div>
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
div {
    background: url("../../assets/eclipse.jpg") no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    width: 100%;
    display: flex;
    align-content: center;
    padding-top: 10%;
}
@media only screen and (min-width: 1000px) {
    div {
        background: url("../../assets/eclipse.jpg") no-repeat fixed;
        background-position: center top;
        padding-top: 5%;
        padding-bottom: 10%;
    }
}
</style>