<template>
    <h1>Custom page {{ title }}</h1>
</template>

<script>
definePageMeta({
    layout : "custom"
});
export default {
    data() {
        return {
            title : 'test'
        }
    }
}
</script>