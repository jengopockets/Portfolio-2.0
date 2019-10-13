<template>
    <div>
    <Title />
    <Profile />
    </div>
</template>
<script>
import Title from "./Title";
import Profile from "./Profile";
export default {
    name: "titleContainer",  
    components: {
        Title,
        Profile
    }  
}
</script>
<style scoped>
div {
    margin-right: 33%;
    margin-left: 33%;
    display: flex;
}
</style>