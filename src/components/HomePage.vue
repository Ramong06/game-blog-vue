<template>
<div class="containter-fluid m-0 p-0">

    <div id="home__page" class="full-height p-4">
        <div class="container pt-3">
            <div class="row pb-5">
                <div class="col-lg-6 pt-4 my-auto">
                    <div class="text-center mb-3 d-block d-lg-none">
                        <h1 class="display-3">{{ title }}</h1>
                        <h3>Talk About Your Game Experience</h3>
                    </div>
                    <img id="starFox" src="../assets/star-fox.png" alt="star-fox-video-game-character">
                </div>
                <div class="col-lg-6 mt-4">
                    <div class="text-center mb-3 d-none d-lg-block">
                        <h1 class="display-3">{{ title }}</h1>
                        <h3>Talk About Your Game Experience</h3>
                    </div>

                    <div class="border p-3 p-md-5 bg-white rounded shadow">
                        <h2>Coming Soon</h2>
                        <form action="">
                            <div class="form-group">
                                <label for="emailSignup">Sign Up For Your Account Now and We Will Contact You When We Are Live!</label>
                                <input id="emailSignup" 
                                placeholder="Enter Email"
                                class="form-control"
                                >
                                <small id="emailHelp" class="form-text text-muted">We Will Never Share Your Email Address</small>
                                <button type="submit" class="btn btn-success mt-3">Join Now</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <div id="about" class="bg-light p-5 p-md-7">
               <div class="container pt-3">
            <div class="row pb-5">
                <div class="col-lg-4 pt-4 my-auto">
                    <img id="nesController" src="../assets/nes-controller.png" alt="nintendo-controller-in-color" height="100" width="170">
                    <h4 class="pt-3">TITLE</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Earum illo eum libero adipisci nesciunt voluptate impedit sequi eaque nobis 
                        deleniti quo nam, reiciendis debitis eos autem tempora sunt itaque dolor!
                    </p>
                </div>

                <div class="col-lg-4 mt-4">
                    <img id="nesController" src="../assets/n64-controller.png" alt="nintendo64-controller" height="120" width="130">
                    <h4 class="pt-3">TITLE</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Earum illo eum libero adipisci nesciunt voluptate impedit sequi eaque nobis 
                        deleniti quo nam, reiciendis debitis eos autem tempora sunt itaque dolor!
                    </p>
                </div>

                <div class="col-lg-4 mt-4">
                    <img id="nesController" src="../assets/mario-switch.png" alt="mario-character-holding-switch" height="140" width="130">
                    <h4 class="pt-3">TITLE</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Earum illo eum libero adipisci nesciunt voluptate impedit sequi eaque nobis 
                        deleniti quo nam, reiciendis debitis eos autem tempora sunt itaque dolor!
                    </p>
                </div>

            </div>

        </div>
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
            title: 'GameBlog',
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
    ), url('../assets/16-bit-skyline.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

#starFox {
    max-height: 80vh;
}

#about {
    min-width: 40vh;
}

</style>
