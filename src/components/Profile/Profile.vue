<template>
    <div class="content">
        <div>
            <img src="https://static.wixstatic.com/media/6d54a9_11d3bd0eb97640dd8b061340a2c08fdf~mv2.jpg" alt=""/>
        </div>
        <div>
            ava + description
        </div>
        <Posts />
    </div>
</template>

<script>
    import Posts from "./Posts";
    export default {
        name: "Profile",
        components: {Posts}
    }
</script>

<style lang="sass" scoped>
.content
    grid-area: c
    background-color: royalblue

    img
        width: 100%
        max-height: 300px


</style>