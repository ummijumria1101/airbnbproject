<template>
    <div>
        <NuxtLink :to="`checkout/` + checkout">
                        
        </NuxtLink>
                    <p>Ini halaman checkout</p>


    </div>
</template>

<script setup>
const { data: product } = await useFetch('https://dummyjson.com/products')


</script>

<style>

</style>