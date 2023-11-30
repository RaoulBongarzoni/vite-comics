<script>

export default {

    props: {
        image: String,
        description: String
    }
}

</script>


<template>
    <slide>
        <div>
            <img :src="image">
            <p>{{ description }}</p>
        </div>
    </slide>
</template>

<style scoped>
div {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-items: center;
    align-items: center;
    margin: 2rem;

}

img {
    width: 70%;
    height: 100%;
    aspect-ratio: 1;
    object-fit: cover;
}

p {

    text-align: center;

    color: white;
}
</style>