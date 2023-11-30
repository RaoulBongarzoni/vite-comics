<script>
import my_buyBar from "./BlueBar.vue"
import my_jumbo_footer from "./Footer_Jumbo.vue"
import my_links from "./Footer_Bottom.vue"

export default {
    components: {
        my_buyBar,
        my_jumbo_footer,
        my_links
    }


}
</script>

<template>
    <my_buyBar />
    <my_jumbo_footer />
    <my_links />
</template>

<style>
.container {
    height: 100%;
    max-width: 900px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    align-items: center;

}
</style>