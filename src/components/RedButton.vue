
<template>
    <div>
        <button>{{ text }}</button>
    </div>
</template>

<script lang="ts">
/* eslint-disable */
import { defineComponent } from "vue";
export default defineComponent({
    name: "RedButton",
    props: {
        text: String,
    }
});
</script>

<style>
    button {
        background-color: #b94279;
        border: solid 1px #743a55;
        border-radius: 10px;
        color: white;
        cursor: pointer;
        font-size: 20px;
        margin: 30px;
        padding: 15px 30px;
        text-transform: uppercase;
    }
    button:hover {
        animation: cubic-bezier(0, 0.45, 0.68, 1.13);
        animation-duration: 5s;
        background-color: #a03768;
    }
</style>