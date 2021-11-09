<template>
    <component :is="layout"></component>
</template>

<script>
import Default from "@/layouts/Default";
import Empty from "@/layouts/Empty";
const defaultLayout = "empty"

export default {
    components: {
        'default-layout': Default,
        'empty-layout': Empty
    },
    data() {
        return {}
    },
    computed: {
        layout() {
            return `${this.$route.meta.layout || defaultLayout}-layout`;
        },
    }
}
</script>
