<template>
    <div id="Pc">
        <div>
        <h1>Projects</h1>
        </div>
        <div id="projects">
            <a href="https://crime-statistics-master.netlify.com/">
            
                <img src="../../assets/Crime.png" alt="Crime Stats Photo" />
            
                <h2>Crime Stats For Travelers</h2>
            </a>
            <a href="https://lucid-panini-415838.netlify.com/">
            
                <img src="../../assets/Random.png" alt="Random Acts Photo" />
            
                <h2>Random Acts</h2>
            </a>
            <a href="https://secret-recipes.netlify.com/">
                
                <img src="../../assets/Secret.png" alt="Secret Recipies Photo" />            
                
                <h2>Secret Family Recipies Cookbook</h2>
            </a>
            <a href="https://connect-our-kids.github.io">
                
                <img src="../../assets/Connect.png" alt="Connect-Our-Kids Photo" />
                
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
#Pc {
    padding-top: 5%;
    padding-bottom: 5%;
    background: rgb(32, 1, 1);
    height: 100%;
}
a {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    text-decoration: none;
    padding: 3rem;
}
h1 {
    text-align: center;
}
@media only screen and (min-width: 600px) {
    #Pc {
        display: flex;
        flex-direction: column;
        align-content: center;
    }
    #projects {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
    }
    
}

</style>