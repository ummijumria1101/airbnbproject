<template>
    <div>
        <NuxtLink :to="`checkout` + checkout">
                        
                    </NuxtLink>

    </div>
</template>

<script setup>
const { data: product } = await useFetch('https://dummyjson.com/products')


</script>

<style lang="scss" scoped>

</style>