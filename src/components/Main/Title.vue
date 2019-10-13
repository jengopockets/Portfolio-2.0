<template>
    <div>
    <div id="titletext">
    <curve-text id="curveboi">JengoDev</curve-text>
    
    <h3>by</h3>
    <h2>Jacob Tharp</h2>
    </div>
    </div>
</template>

<script>
import CurveText from '@inotom/vue-curve-text';

export default {
    name: "title",
    components: {
        CurveText
    }
}
</script>

<style scoped>
@font-face {
  font-family: andromeda;
  src: url(../../assets/andromeda.ttf);
}
h1 {
    opacity: 1;   
}
div {    
    display: flex;
    flex-direction: column;
    align-items: center; 
}
#titletext {   
    opacity: 1;
}
#curveboi {
    font-size: 34px;
}
@media only screen and (min-width: 1000px) {
    #titletext {
        font-size: 40px;
    }
    #curveboi {
    font-size: 45px;
    overflow: visible;
}

}
</style>