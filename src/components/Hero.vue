<template>
 <div>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Chi siamo</a></li>
        <li><a href="#">Contatti</a></li>
    </ul>
 </div>
    
</template>

<script>
export default {
    name: "Hero"
}
</script>

<style lang="scss" scoped>
li{
    display: inline;
}
ul{
    list-style-type: none;
}

a{
    padding-top: 40px;
    margin-left:50px;
}
// // template{
// //     background-image: url(".\src\assets\background.webp");
// // }

div{
    background-color:darkgoldenrod;
    width: 100%;
    height: 70vh;
}

 
</style>