<script>
import cards_holder from "../components/main_content/CardHolder.vue"
import Jumbo from "../components/main_content/Jumbo.vue";
export default {
    components: {
        Jumbo,
        cards_holder
    }
}
</script>


<template>
    <div id="main">



        <Jumbo />

        <div class="container">
            <div id="target">


                TRENDING

            </div>

            <cards_holder />
        </div>
    </div>
</template>

<style scoped>
#main {
    background-color: #222;

}



#target {

    position: absolute;
    top: -3%;
    border: 2px solid red;
    color: white;
    font-size: large;
    font-weight: bold;
    background-color: blue;
    padding: 1rem;
}

.container {
    position: relative;
    height: 100%;
    max-width: 900px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    align-items: center;

}
</style>