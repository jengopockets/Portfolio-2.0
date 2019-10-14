<template>
    <div id="Pc">
        <h1>Projects</h1>
        <div id="project">
            <a href="https://crime-statistics-master.netlify.com/">
            <div id="img">
                <img src="../../assets/Crime.png" alt="Crime Stats Photo" />
            </div>
            <h2>Crime Stats For Travelers</h2>
            </a>
        </div>
        <div id="project">
            <a href="https://lucid-panini-415838.netlify.com/">
            <div id="img">
                <img src="../../assets/Random.png" alt="Random Acts Photo" />
            </div>
            <h2>Random Acts</h2>
            </a>
        </div>
        <div id="project">
            <a href="https://secret-recipes.netlify.com/">
                <div id="img">
                    <img src="../../assets/Secret.png" alt="Secret Recipies Photo" />            
                </div>
                <h2>Secret Family Recipies Cookbook</h2>
            </a>
        </div>
        <div id="project">
            <a href="https://connect-our-kids.github.io">
                <div id="img">
                    <img src="../../assets/Connect.png" alt="Connect-Our-Kids Photo" />
                </div>
                <h2>Connect-Our-Kids</h2>
            </a>
        </div>
        
    </div>    
</template>

<script>
export default {
    name:'projects'
    
}
</script>

<style scoped>

a {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}
h1 {
    text-align: center;
}

</style>