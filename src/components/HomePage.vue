<template>
<div class="containter-fluid m-0 p-0">

    <div id="home__page" class="full-height p-4">
        Hello
    </div>

    <div id="about" class=" bg-warning p-4">
        Hello
    </div>

    <div id="contact" class="bg-info p-4">
        Hello
    </div>

    <div id="footer" class="bg-primary p-4">
        Hello
    </div>

</div>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#home__page {
    background-color: aqua;
    background: url('../assets/mountain-and-lake.jpg') no-repeat center center;
    opacity: 90%;
    filter: brightness(75%);
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

</style>
