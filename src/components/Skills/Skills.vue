<template>
    <div id="skills">
        <div id="head">
            <h2>Skills</h2>
        </div>
        <div id="img">
            <img src="../../assets/React.png" alt="React Logo"/>
            <img src="../../assets/Javascript.png" alt="JavaScript Logo"/>
            <img src="../../assets/Node.png" alt="Node Logo"/>
        </div>
        
    </div>    
</template>

<script>
export default {
    name:'skill'
      
}
</script>

<style scoped>
#skills {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgb(2, 0, 26);

}
#img , img{
    display: flex;
    flex-direction: column;
    width: 360px;
}
@media only screen and (min-width: 1500px) {
    #skills {
    display: flex;
    flex-direction: column;
    align-items: center;
    background: rgb(2, 0, 26);

    }
    #img , img{
        display: flex;
        flex-direction: row;
        justify-content: center;
        width: 360px;
        padding-bottom: 5%;
    }
}



</style>