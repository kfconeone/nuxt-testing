<script lang="ts" setup>
import { onMounted } from "vue";
import gsap from "gsap";

onMounted(() => {
    console.log("mounted");
    gsap.to(".gg", { x: 100 });
});
</script>

<template>
    <div>
        <div class="gg">asdasd</div>
    </div>
</template>
