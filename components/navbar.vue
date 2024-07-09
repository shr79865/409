<template>
    <div class="flex justify-between bg-[#eeeeee] px-[80px] py-[20px] shadow-b-xl">

        <div class="flex gap-5 items-center">
            <img class="rounded-full" src="../public/410_logo_img.webp" alt="logo" width="30">

            <div class="relative">
                <input class="w-[250px] px-[20px] pr-[38px] py-[7px] rounded-full focus:outline-none" type="text"
                    placeholder="Search">
                <button class="absolute text-[20px] top-[3px] right-[10px] font-semibold hover:text-[#5578ec]"><i
                        class="ri-search-line"></i></button>
            </div>

            <nuxt-link
                class="bg-gradient-to-r from-pink-500 to-red-500 font-bold hover:scale-[1.1] shadow-lg hover:shadow-2xl text-[17px] duration-300 text-[#ffffff] px-[15px] py-[7px] rounded-full"
                to="/Uevents">Upcoming Events</nuxt-link>

        </div>



        <div class="flex gap-[40px] font-semibold text-[18px] text-[#000000] items-center">
            <nuxt-link
                class="duration-300 hover:shadow-2xl hover:text-[#ffffff] hover:bg-gradient-to-r from-sky-500 to-indigo-500 hover:rounded-full hover:px-[15px] hover:py-[5px]"
                to="/">HOME</nuxt-link>
            <nuxt-link
                class="duration-300 hover:shadow-2xl hover:text-[#ffffff] hover:bg-gradient-to-r from-sky-500 to-indigo-500 hover:rounded-full hover:px-[15px] hover:py-[5px]"
                to="/connect">CONNECT</nuxt-link>
            <nuxt-link
                class=" duration-300 hover:shadow-2xl hover:text-[#ffffff] hover:bg-gradient-to-r from-sky-500 to-indigo-500 hover:rounded-full hover:px-[15px] hover:py-[5px]"
                to="/about">ABOUT</nuxt-link>
            <nuxt-link
                class="duration-300 hover:shadow-2xl hover:text-[#ffffff] hover:bg-gradient-to-r from-sky-500 to-indigo-500 hover:rounded-full hover:px-[15px] hover:py-[5px]"
                to="/contact">CONTACT</nuxt-link>
        </div>

    </div>
</template>

<script setup>

</script>

<style scoped></style>