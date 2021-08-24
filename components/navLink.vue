<template>
    <div>
        <a class="nav_link">{{title}}</a>
    </div>
</template>

<script>
    export default {
        props: {
            title: {
                type: String,
                required: true
            },
        },
    }
</script>
<style>
    .nav_link {
        font-size: 14px;
        font-family: "SF Pro Regular";
    }

    .nav_link:hover {
        color: #5469D4;
    }
</style>