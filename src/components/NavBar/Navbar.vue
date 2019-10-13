<template>
    <div>
    <a>About</a>
    <a>Skills</a>
    <a>Projects</a>
    <a>Contact</a>
    <a>Resume</a>
    </div>
</template>
<script>
export default {
    name: "navbar"
}
</script>
<style scoped>
@font-face {
  font-family: andromeda;
  src: url(../../assets/andromeda.ttf);
}
div {
    width: 100%;
    height: 10%;
    position: fixed;
    opacity: .5;
    background: linear-gradient(214deg, rgba(144,1,23,1) 0%, rgba(0,0,0,1) 39%);
    display: flex;
    justify-content: flex-start;
    align-items: center;
}
 div:hover {
    opacity: 1;
}
a {
    padding-right: 2rem;
    font-family: andromeda;
    font-size: 2rem;
}

</style>