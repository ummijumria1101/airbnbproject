<template>
    <div>
        <div class="search-cont inline-flex gap-2 bg-white p-2 rounded-lg shadow-lg">
          <input class="px-2 outline-none" type="search" name="search" id="search">
          <button class="bg-blue-600 text-white px-2 rounded-md" type="submit">Search</button>
        </div>
        <p>{{ product.title }}</p>
        <ul class="prose prose-xl">
          <!-- list out all fetched articles --> 
        <li v-for="article in product" :key="article.id">
          <nuxt-link :to="{ name: 'blog-slug', params: { slug: article.slug } }">
            <h2 class="mb-0">{{ article.title }}</h2>
            <p class="mt-0">{{ article.description }}</p>
          </nuxt-link>
        </li>
      </ul>
    </div>


        
</template>

<script setup>
    const { cat } = useRoute().params
    const uri = 'https://dummyjson.com/products/categories' + cat

    // fetch
    const { data: product } = await useFetch(uri)
    
    // definePageMeta({
    //     layout : 'products'
    // })
    

</script>

<style lang="scss" scoped>

</style>
