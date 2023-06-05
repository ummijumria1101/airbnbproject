<template>
    <div>
        <p>lalala</p>
        <p>{{ product.title }}</p>

    </div>
</template>

<script setup>

const { id } = useRoute().params
    const uri = 'https://dummyjson.com/products/' + id

    // fetch
    const { data: product } = await useFetch(uri)

</script>

<style lang="scss" scoped>

</style>