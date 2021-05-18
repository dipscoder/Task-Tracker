<template>
    <button @click="myClick()" :style="{background: color}" class="btn">{{text}}</button>
</template>

<script>
export default {
    name: "Button",
    props: {
        text: String,
        color: String,
    },
    methods: {
        myClick() {
            console.log("Clicked");
        }
    },
}
</script>