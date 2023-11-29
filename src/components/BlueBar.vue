<script>
export default {
    name: "buyClicks",
    data() {
        return {
            components: [
                {
                    img: "src/assets/buy-comics-digital-comics.png",
                    text: "DIGITAL COMICS"

                },
                {
                    img: "src/assets/buy-comics-merchandise.png",
                    text: "DC MERCHANDISE"

                },
                {
                    img: "src/assets/buy-comics-shop-locator.png",
                    text: "SUBSCRIPTION"

                },
                {
                    img: "src/assets/buy-comics-subscriptions.png",
                    text: "COMIC SHOP LOCATIION"

                },
                {
                    img: "src/assets/buy-dc-power-visa.svg",
                    text: "DC POWER VISA"

                },



            ]

        }


    }

}


</script>

<template>
    <div id="blue">
        <div class="container">
            <div v-for="card in components" class="card">
                <img :src="card.img" alt="">
                <p>{{ card.text }}</p>
            </div>


        </div>
    </div>
</template>

<style scoped>
#blue {
    background-color: blue;
    height: 100%;
    padding: 1rem;
}

.card {
    height: 5rem;

    display: flex;
    justify-content: center;
    align-items: center;
    width: calc(100% / 5);
}

p {
    color: white;
    font-weight: bold;
    font-size: x-small;


}

img {
    max-height: 100%;
    max-width: 50%;


}

.container {
    height: 100%;
    max-width: 900px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    align-items: center;

}
</style>