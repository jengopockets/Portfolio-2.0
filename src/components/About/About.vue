<template>
    <div id="about">
        <div id="text">
            <h2>About</h2>
            <p>
            I am a Full Stack Web Developer, currently studying at Lambda School. I've taken my first dip in the development world and crave to get more of it. I am fluent with React and Node.js, and am currently learning the Vue.js Framework. I also have a basic understanding of SQL, and am intrested in learning about C#, Python, and Java. In my free time I like to do work on my D&D Campaign that I DM on the weekends.
            </p>
        </div>
        <div id="image">
        <img src="../../assets/profile.png"/>
        </div>
    </div>    
</template>
<script>
export default {
    name: 'about',
    components: {

    }
    
}
</script>
<style scoped>
#about {
    background: black;
    display: flex;
    opacity: 1;
}
#text {
    display: flex;
    flex-direction: column;
}
h2 {
    align-self: center;
}
img {
    display: none;
}
@media only screen and (min-width: 600px) {
    img {
        display: initial;
        width: 100%;
    }    
    #about {
        flex-direction: column;
    }
}
</style>