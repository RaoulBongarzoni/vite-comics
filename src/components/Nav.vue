<script>
export default {
    name: "links",
    data() {
        return {
            menu: [

                {
                    name: "characters",
                    src: "#"

                },
                {
                    name: "comics",
                    src: "#"

                },
                {
                    name: "movies",
                    src: "#"

                },
                {
                    name: "tv",
                    src: "#"

                },
                {
                    name: "games",
                    src: "#"

                },
                {
                    name: "collectibles",
                    src: "#"

                },

            ]
        }




    }


}

</script>

<template>
    <div class="section">
        <div class="container">
            <img src="../assets/favicon.ico" alt="">
            <div>

                <a v-for="link in menu " :href="link.src">{{ link.name }}</a>
            </div>


        </div>

    </div>
</template>

<style>
.section {
    background-color: white;
    width: 100%;
    height: 4rem;
}

/* .container {
    height: 100%;
    max-width: 900px;
    display: flex;
    justify-content: space-between;

    margin: 0 auto;
    align-items: center;

}
 */
img {
    height: 100%;
    padding: 1rem;
}

a {
    text-decoration: none;
    margin: 0 1rem;
    color: #222;

}
</style>