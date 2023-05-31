<template>
    <div class="flex border-b-2 h-[81px] items-center justify-between">
        <NuxtLink to="/">
            <img src="/img/airbnbpinklogo.png" class="h-[81px] w-auto items-center">
        </NuxtLink>
    </div>
    <div>
        <div class="flex ml-[70px] mt-[30px]">
            <NuxtLink to="/details">
                <div>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mt-[10px]">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
                </svg>
            </div>
            </NuxtLink>

            <h1 class="ml-[10px] text-4xl font-medium text-gray-900 items-center">Ajukan Pemesanan</h1>
        </div>
        <div class="flex mt-[30px]">
            <div class="w-[570px] ml-[100px] border-b-2">
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



                <div class="border-b-2 pb-[30px]">
                    <p class="my-[20px] font-medium text-2xl">Pilih cara membayar</p>
                    <div class="border-2 rounded-lg">
                    <!-- pilih cara bayar -->
                        <div class="p-2">
                            <div class="flex justify-between rounded-lg items-center">
                                <p class="text-lg font-semibold">Bayar secara penuh</p>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 9.563C9 9.252 9.252 9 9.563 9h4.874c.311 0 .563.252.563.563v4.874c0 .311-.252.563-.563.563H9.564A.562.562 0 019 14.437V9.564z" />
                                </svg>
                            </div>
                            <p>Bayar biaya total (Rp6.847.702,29) sekarang dan semua selesai.</p>
                        </div>
                        <div class="p-2">
                            <div class="flex justify-between rounded-lg items-center">
                                <p class="text-lg font-semibold">Bayar secara penuh</p>
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 9.563C9 9.252 9.252 9 9.563 9h4.874c.311 0 .563.252.563.563v4.874c0 .311-.252.563-.563.563H9.564A.562.562 0 019 14.437V9.564z" />
                                </svg> 
                            </div>
                            <p>Bayar biaya total (Rp6.847.702,29) sekarang dan semua selesai.</p>
                        </div>
                    </div>
                </div>

                <div class="my-[30px] pb-[20px] border-b-2">
                    <div>
                        <p class="mb-[20px] font-medium text-2xl">Diperlukan untuk perjalanan anda</p>
                    </div>
                    <div>
                        <!-- ini isi -->
                        <div class="pb-[10px]">
                            <div class="flex justify-between items-center">
                                <p class="font-medium text-lg">Kirim pesan kepada tuan rumah</p>
                                <div class="border-[1px]  border-black px-3 py-1 rounded-md hover:bg-slate-100">
                                    <p>tambah</p>
                                </div>
                            </div>
                            <div class="mr-[70px]">
                                Beri tahu tuan rumah alasan perjalanan Anda dan kapan Anda akan check-in.
                            </div>
                        </div>
                        <div class="pb-[10px]">
                            <div class="flex justify-between items-center">
                                <p class="font-medium text-lg">Foto profil</p>
                                <div class="border-[1px]  border-black px-3 py-1 rounded-md hover:bg-slate-100">
                                    <p>tambah</p>
                                </div>
                            </div>
                            <div class="mr-[70px]">
                                Tuan rumah ingin mengetahui siapa yang akan menginap di tempatnya.
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between items-center">
                                <p class="font-medium text-lg">Nomor telepon</p>
                                <div class="border-[1px]  border-black px-3 py-1 rounded-md hover:bg-slate-100">
                                    <p>tambah</p>
                                </div>
                            </div>
                            <div class="mr-[70px]">
                                Tambahkan dan konfirmasikan nomor telepon Anda untuk mendapatkan info terbaru perjalanan.
                            </div>
                        </div>
                    </div>

                </div>
                <div class="my-[30px] pb-[20px] border-b-2">
                    <div>
                        <p class="mb-[20px] font-medium text-2xl">Kebijakan pembatalan</p>
                    </div>
                    <div>
                        <!-- ini isi -->
                        <p class="text-justify">
                            <b>Pembatalan gratis sebelum 11 Jul.</b> Jika dibatalkan sebelum check-in pada tanggal 12 Jul, Anda akan mendapatkan pengembalian uang sebagian. <br> <b>Pelajari selengkapnya</b>
                        </p>
                    </div>

                </div>
                <div class="my-[30px] pb-[20px] border-b-2">
                    <div>
                        <p class="mb-[20px] font-medium text-2xl">Aturan dasar</p>
                    </div>
                    <div>
                        <!-- ini isi -->
                        <p class="text-left">
                            Kami meminta setiap tamu untuk mengingat beberapa hal sederhana mengenai apa saja yang perlu dilakukan untuk menjadi tamu yang luar biasa.
                        </p>
                        <ul class="list-disc ml-[20px]">
                            <li>Patuhi peraturan rumah</li>
                            <li>Perlakukan rumah milik Tuan Rumah Anda seperti rumah Anda sendiri</li>
                        </ul>
                    </div>

                </div>
                <div class="my-[30px] pb-[20px] border-b-2">
                    <div class="flex items-center gap-4">
                        <!-- ini isi -->
                        <div class="">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 012.25-2.25h13.5A2.25 2.25 0 0121 7.5v11.25m-18 0A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75m-18 0v-7.5A2.25 2.25 0 015.25 9h13.5A2.25 2.25 0 0121 11.25v7.5m-9-6h.008v.008H12v-.008zM12 15h.008v.008H12V15zm0 2.25h.008v.008H12v-.008zM9.75 15h.008v.008H9.75V15zm0 2.25h.008v.008H9.75v-.008zM7.5 15h.008v.008H7.5V15zm0 2.25h.008v.008H7.5v-.008zm6.75-4.5h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V15zm0 2.25h.008v.008h-.008v-.008zm2.25-4.5h.008v.008H16.5v-.008zm0 2.25h.008v.008H16.5V15z" />
                            </svg>
                        </div>
                        <div>
                            <b>Reservasi Anda tidak akan terkonfirmasi sebelum tuan rumah menyetujui permohonan Anda (dalam 24 jam).</b> <br>
                            Anda tidak akan dikenakan biaya sampai saat itu.
                        </div>
                    </div>

                </div>

                <div class="mb-[20px]">
                    <p class="text-xs">Dengan memilih tombol di bawah ini, saya menyetujui <b>Peraturan Tuan Rumah, Aturan dasar untuk tamu, Kebijakan Pemesanan Ulang dan Pengembalian Uang Airbnb, dan bahwa Airbnb bisa membebankan biaya ke metode pembayaran saya</b> jika saya bertanggung jawab atas kerusakan. Saya setuju untuk membayar jumlah total yang tertera jika Tuan Rumah menyetujui permohonan pemesanan saya.</p>
                </div>

                <div class="py-3 justify-start bg-pink-600 mx-[150px] mt-[10px] rounded-md hover:bg-pink-500 mb-[30px]">
                    <p class="text-center text-xs px-2 font-bold text-white lg:text-lg lg:px-3">Ajukan Pemesanan</p>
                </div>

            </div>
            <div class="top-[150px] bottom-[100px] left-[800px] right-[80px]">
                <!-- ini buat card detail pemesanan -->
                <div class="sticky top-20 border-2 p-[24px] ml-[110px] w-[477px] h-[509px] mr-[80px] rounded-lg">
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