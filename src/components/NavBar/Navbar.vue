<template>
    <div>
    <h2>About</h2>
    <h2>Skills</h2>
    <h2>Projects</h2>
    <h2>Contact</h2>
    <h2>Resume</h2>
    </div>
</template>
<script>
export default {
    name: "navbar"
}
</script>
<style scoped>
div {
    width: 100%;
    color:white;
    height: 10%;
    position: fixed;
    opacity: .5;
    background: linear-gradient(214deg, rgba(144,1,23,1) 0%, rgba(0,0,0,1) 39%);
    display: flex;
    justify-content: flex-start;
}
 div:hover {
    opacity: 1;
}
h2 {
    padding-right: 2rem;
}

</style>