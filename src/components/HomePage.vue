<template>
<div class="containter-fluid m-0 p-0">

    <div id="home__page" class="full-height p-4">
        <div class="container pt-3">
            <div class="row pb-5">
                <div class="col-lg-6 pt-4 my-auto">
                    <img id="stewardess" src="../assets/stewardess.jpg" alt="stewardess">
                </div>
                <div class="col-lg-6">
                    <div class="text-center mb-3">
                        <h1 class="display-3">{{ title }}</h1>
                        <h3>Travel the World</h3>
                    </div>
                </div>
            </div>

        </div>
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
    data () {
        return {
            title: 'Travel Treasury',
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
    color: rgba(255, 255, 255, 0.872);
}

h3 {
    color: rgba(255, 255, 255, 0.865);
}

#home__page {
    background: linear-gradient(
      rgba(0, 0, 0, 0.5),
      rgba(0, 0, 0, 0.5)
    ), url('../assets/mountain-and-lake.jpg') no-repeat center center;
    filter: contrast(85%);
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

#stewardess {
    max-height: 80vh;
    max-width: 80vh;
}

</style>
