<template>
    <div id="contact">
        <div id="social">
        <a id="twit" href="https://twitter.com/JacobTharp12" class="fa fa-twitter"></a>
        <a id="resume" href="./Resume.pdf" download="Jacobs-Resume.pdf" class="fa fa-download">Download Resume</a>
        <a id="link" href="https://www.linkedin.com/in/jacob-tharp-79382311b/" class="fa fa-linkedin"></a>
        </div>

    </div>
</template>

<script>
export default {
    name: 'contacts'    
}
</script>

<style scoped>
a {
    padding: 2rem;    
    font-style: normal;
    text-decoration: none;
    color: white;
}
#social {
    display: flex;
    justify-content: space-around;
}
#link {
    background-color: #007bb5;
    border-radius: 50%;
    font-size: 5rem;
}
#twit {
    background-color: #55ACEE;
    border-radius: 50%;
    font-size: 5rem;
}
#resume {
    font-size: 3rem;
}

</style>