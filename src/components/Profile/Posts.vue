<template>
    <div class="">
        My posts
        <div>
            <textarea name="" id="" cols="30" rows="3"></textarea>
            <button>add post</button>
        </div>
        <div class="posts">
            <Post post-title="hello! bla bla!" v-bind:post-likes="15" />
            <Post post-title="ho ho ho! oooo" v-bind:post-likes="42" />
        </div>
    </div>
</template>

<script>
    import Post from "./Post";
    export default {
        name: "Posts",
        components: {Post},

    }
</script>

<style lang="sass" scoped>


</style>