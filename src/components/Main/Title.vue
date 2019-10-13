<template>
    <div>
    <div id="title">
    <h1>JengoDev</h1>
    <h3>by</h3>
    <h2>Jacob Tharp</h2>
    </div>
    </div>
</template>

<script>
export default {
    name: "title",
}
</script>

<style scoped>
h1 {
    opacity: 1;     
}
div {
    display: flex;
    flex-direction: column;
    align-items: center;
    
}
#title {   
    color: white; 
    border: 2px solid rgb(5, 3, 32);
    opacity: 1;
}
</style>