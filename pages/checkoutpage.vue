<template>
        <div class="flex border-2 h-[81px] items-center justify-between">
        <img src="/img/airbnbpinklogo.png" class="h-[81px] w-auto items-center">
    </div>
    <div>
        <div class="flex ml-[70px] mt-[30px]">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mt-[10px]">
  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
</svg>

            <h1 class="ml-[10px] text-4xl font-medium text-gray-900 items-center">Ajukan Pemesanan</h1>
        </div>
        <div class="flex mt-[30px] justify-between">
            <div class="w-1/3 ml-[100px] border-b-2">
                <p class="font-medium text-2xl">Perjalanan Anda</p>
                <div class="mt-[20px]">
                    <div class="flex justify-between">
                    <p class="font-semibold text-lg">Tanggal</p>
                    <p class="font-semibold underline underline-offset-1">Edit</p>
                    </div>
                    <p>20-25 Jul</p>
                </div>
                <div class="mt-[20px] mb-[10px]">
                    <div class="flex justify-between">
                    <p class="font-semibold text-lg">Tamu</p>
                    <p class="font-semibold underline underline-offset-1">Edit</p>
                    </div>
                    <p>1 tamu</p>
                </div>

            </div>
            <div>
                <!-- ini buat card detail pemesanan -->
                <div class="border-2 p-[24px] ml-4 w-[477px] h-[509px] mr-[80px] rounded-lg">
                    <div class="flex gap-2 border-b-2 pb-[20px]">
                        <div>
                            <img src="/img/superhost.png" class="w-[124pxpx] h-[106px] rounded-lg">
                        </div>
                        <div>
                        <div>
                            <!-- ini detail dan review dll -->
                            <p class="text-gray-600 text-sm">Seluruh vila</p>
                            <p CLASS="text-gray-800">Villa Pavilion Garden dengan KOLAM RENANG PRIBADI</p>
                            <div class="flex mt-[20px] items-center gap-[3px] justify-between">
                                <div class="flex gap-[3px] items-center">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-3 h-3">
  <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
</svg>
                                <p class="text-sm font-medium">4.92</p>
                                <p class="text-gray-600 text-sm">(96 ulasan)</p>
                                </div>
                                

                                <div class="flex gap-[3px] items-center mr-[10px]">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
  <path d="M14.916 2.404a.75.75 0 01-.32 1.012l-.596.31V17a1 1 0 01-1 1h-2.26a.75.75 0 01-.75-.75v-3.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.5a.75.75 0 01-.75.75h-3.5a.75.75 0 010-1.5H2V9.957a.75.75 0 01-.596-1.372L2 8.275V5.75a.75.75 0 011.5 0v1.745l10.404-5.41a.75.75 0 011.012.32zM15.861 8.57a.75.75 0 01.736-.025l1.999 1.04A.75.75 0 0118 10.957V16.5h.25a.75.75 0 110 1.5h-2a.75.75 0 01-.75-.75V9.21a.75.75 0 01.361-.64z" />
</svg>
<p class="text-gray-600 text-sm">HostTeladan</p>
                                </div>
                                


                            </div>

                        </div>
                    </div>

                    </div>

                    <div>
                        <div class="my-[30px]">
            <!-- Perincian harga -->
            <p class="text-2xl font-medium text-gray-800">Perincian harga</p>

        </div>
        <div class="pb-[30px] border-b-2">
            <div class="flex justify-between">
            <p class="text-gray-600">Rp3.000.000,00 x 2 malam</p>
            <p class="text-gray-600">Rp6.000.000,00</p>

        </div>
        <div class="flex justify-between">
            <p class="text-gray-600 underline underline-offset-1">Diskon menginap jangka panjang</p>
            <p class="text-green-600">-Rp180.000,00</p>

        </div>
        <div class="flex justify-between">
            <p class="text-gray-600 underline underline-offset-1">Biaya kebersihan</p>
            <p class="text-gray-600">Rp100.000,00</p>

        </div>
        <div class="flex justify-between">
            <p class="text-gray-600 underline underline-offset-1">Biaya layanan Airbnb</p>
            <p class="text-gray-600">Rp927.720,29</p>

        </div>
        </div>
        <div class="flex justify-between mt-[20px]">
            <p class="text-xl font-bold underline underline-offset-1">Total (IDR)</p>
            <p class="text-xl font-bold">Rp6.847.702,29</p>

        </div>
                    </div>


            
        </div>
        
            </div>

        </div>
        

    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>