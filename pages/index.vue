<template>
    <div class="bg-[url('/img/bg.png')] bg-fixed bg-cover h-screen">
        <div >
            <div class="grid grid-cols-4">
                <div class="pl-[25.65px] pt-[15.61px]">
                    <img src="/img/icons8-airbnb-50.png" class="w-[28.65px] h-[30.78px]">
                </div>

                <nav class="flex col-span-3 place-items-end ml-[200px] mt-[15.61px]">
                    <div class="items-center">
                        <ul class="flex md:flex-row sm:flex-col xs:flex-col items-center place-content-end py-2 gap-5">
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Français (FR)</NuxtLink></li>
                            <li class=""><NuxtLink to="https://twitter.com" class="hover:text-gray-300">EUR €</NuxtLink></li>
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Devenir hôte</NuxtLink></li>
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Créer son expérience</NuxtLink></li>
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Aide</NuxtLink></li>
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Inscription</NuxtLink></li>
                            <li><NuxtLink to="/about" class="hover:text-gray-300">Connexion</NuxtLink></li>
                            <li><button class="items-center place-content-center bg-[#a6c1ee] text-white px-5 py-2 rounded-lg hover:bg-[#87acec] ml-[10px]">Sign in</button></li>
                        </ul>
                        
                    </div>
                    <div  class="absolute">
                        
                    </div>
                </nav>


                
                <!-- <div class="max-w-6xl mx-auto px-4 flex gap-5 text-white absolute top-[27px] right-[24px]">
                    <NuxtLink to="/about" class="gap-3">Français (FR)</NuxtLink>
                    <NuxtLink to="https://twitter.com" class="gap-3">EUR €</NuxtLink>
                    <NuxtLink to="/about" class="gap-3">Devenir hôte</NuxtLink>
                    <NuxtLink to="/about" class="gap-3">Créer son expérience</NuxtLink>
                    <NuxtLink to="/about" class="gap-3">Aide</NuxtLink>
                    <NuxtLink to="/about" class="gap-3">Inscription</NuxtLink>
                    <NuxtLink to="/about" class="gap-3">Connexion</NuxtLink>
                </div> -->

               

                <div class="grid col-span-1 bg-white w-[350px] h-[450px] mt-[132px] ml-[30px] rounded-md">
                    <div class="px-[24px] pt-[32px] text-2xl">
                        <p class="text-gray-600 font-semibold">Pesan akomodasi dan nikmati aktivitas tak terlupakan seumur hidup!</p>
                    </div>
                </div>
            </div>
       
        </div>
    </div>
    <div class="">
        <explorer />

        <temukan />

        <villa />

        <petualangan />
        
        <destinasi />        
    </div>
</template>
