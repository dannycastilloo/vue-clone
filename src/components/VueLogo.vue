<script>

export default {
    name: 'VueLogo'
}

</script>

<template>
    <div class="vue-logo">
        <img src="/favicon.ico" alt="vue">
        <span>Vue.js</span>
    </div>
</template>

<style>
.vue-logo {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
}

.vue-logo > img {
    width: 24px;
}

.vue-logo > span {
    font-size: 16px;
}
</style>