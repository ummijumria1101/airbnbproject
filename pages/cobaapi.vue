<template>
    <!-- <div>
        <div class="" v-for="barang in result.products" :key="result.id">
                        <div>
                            <div>
                                <img :src="result.thumbnail" class="w-[188px] h-[240px] rounded-md">
                            </div>
                            <div>
                                <p class="text-[16px] p-[1px] text-gray-600 font-bold mt-1">{{ result.title }}</p>                                       
                                <p class="text-[10px] text-px-[3px] text-justify">${{ result.description }}</p>
                                <p class="text-[14px] text-start text-gray-600 font-bold">${{ result.price }}</p>
                            </div>
                        </div>  
        </div>


    </div> -->
    result
    <div id="result2"></div>
</template>

<script setup>
const url = 'https://airbnb19.p.rapidapi.com/api/v1/getCategory';
const options = {
	method: 'GET',
	headers: {
		'X-RapidAPI-Key': '9c505dacabmshc6c8898cbe83df4p17edf7jsn6266d4100c76',
		'X-RapidAPI-Host': 'airbnb19.p.rapidapi.com'
	}
};

try {
	const response = await fetch(url, options);
	const result = await response.text();
	console.log(result);
    const resultElement = document.getElementById("result2");
      resultElement.innerHTML = JSON.stringify(data);
} catch (error) {
	console.error(error);
}
</script>

<style lang="scss" scoped>

</style>