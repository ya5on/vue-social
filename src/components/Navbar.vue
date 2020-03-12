<template>
    <nav class="nav">
        <div class="item active"><a href="">Profile</a></div>
        <div class="item"><a href="">Messages</a></div>
        <div class="item"><a href="">News</a></div>
        <div class="item"><a href="">Music</a></div>
        <div class="item"><a href="">Settings</a></div>
    </nav>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style lang="sass" scoped>
    .nav
        grid-area: n
        background-color: #06B669

    .item
        color: aqua
        padding: 10px

    .active
        text-decoration: underline
</style>