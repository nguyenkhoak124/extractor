<template>
    <q-page class="flex flex-center">
        <img alt="Quasar logo" src="https://cdn.quasar.dev/logo-v2/svg/logo.svg" style="width: 200px; height: 200px">
    </q-page>
</template>

<script>
export default {
    name: 'HelloWorld'
}
</script>

<style scoped>
img {
    border-radius: 50%;
    height: 38px;
    margin-right: 8px;
    transform: rotate(0deg);
    transition: transform .8s ease-in-out;
    width: 38px;
}
img:hover {
    transform: rotate(-1turn);
}
</style>