<script>

export default {
    data() {
        return {

            socialLinks: [

                {
                    name: "Facebook",
                    img: "/images/footer-facebook.png",
                    href: "#"

                },
                {
                    name: "Twitter",
                    img: "/images/footer-twitter.png",
                    href: "#"
                },
                {
                    name: "Youtube",
                    img: "/images/footer-youtube.png",
                    href: "#"
                },
                {
                    name: "Pinterest",
                    img: "/images/footer-pinterest.png",
                    href: "#"
                },
                {
                    name: "Periscope",
                    img: "/images/footer-periscope.png",
                    href: "#"
                },




            ]

        }


    }


}
</script>

<template>
    <div id="row">
        <div class="container">
            <button>sign up here</button>
            <div style="display: flex; align-items: center;">

                <a href="#">FOLLOW US</a>
                <a v-for="obj in socialLinks" :href="obj.href">
                    <img :src="obj.img" :alt="obj.name">
                </a>

            </div>




        </div>
    </div>
</template>

<style scoped>
#row {
    background-color: #222;
    height: 6rem;
    width: 100%;
}

.container {
    height: 100%;
    max-width: 900px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    align-items: center;

}

a {
    color: blue;
    font-size: large;
}

button {

    background-color: transparent;
    border: 2px solid blue;
    font-size: large;
    color: white;
    padding: 1rem;

}
</style>