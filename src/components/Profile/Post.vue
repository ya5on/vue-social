<template>
    <div>
        <div class="item">
            <img src="https://lh3.googleusercontent.com/proxy/8_qxJewb9NZT-_5fUyFPzKWr6Q5gmCwlOCwTpxIpPo1NI2_OmkTgNUfG30XgovgJD7jE-R71Pb0_sIYcN1uE8bxpFOitTjF7qxhQCMfKn02-kMPt7R-TJA5jOQ"
                 alt="">
            {{ postTitle }}
            <div>
                <span>likes: {{ postLikes }}</span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Post",
        props: {
            postTitle: String,
            postLikes: Number,
        }
    }
</script>

<style lang="sass" scoped>
.item
    margin: 5px
    background-color: lightblue
    img
        width: 50px
        height: 50px
        border-radius: 50%
        display: block



</style>