<script>

export default {



    data() {
        return {

            background: "/images/footer-bg.jpg",
            background_logo: "/images/dc-logo-bg.png"


        }

        /* inserire array per lista link */


    }


}

</script>

<template>
    <div id="background">
        <img :src="background" alt="background" id="background_img">
        <div class="container">

            <img :src="background_logo" alt="bg_logo" id="logo">
        </div>
    </div>
</template>


<style scoped>
#background {
    position: relative;
    width: 100%;
    height: 25rem;

}

#background_img {
    position: absolute;
    margin: 0;
    padding: 0;
    width: 100%;
    z-index: -1;
    object-fit: cover;
}

#logo {
    position: absolute;
    top: -10%;
    right: 15%;
    margin: 0;
    padding: 0;
    height: 30rem;
    z-index: -1;

}
</style>