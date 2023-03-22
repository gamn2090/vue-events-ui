<template>
    <div id="CenterCallToAction">
        <div class="px-4 md:w-3/4 lg:w-2/3 mx-auto text-center">
            <h1 class="text-4xl sm:text-5xl md:text-5xl leading-tight text-center text-gray-300 mb-3">
                <b>Events System</b>
            </h1>
            <p class="pt-2 text-xl text-center text-gray-400">
                Welcome to XXXXXX Where you can find the best events, festivals and concerts!
            </p>
        </div>
        <div class="mt-6"></div>
        <div class="flex justify-between">
            <router-link to="/login" class="w-full mr-1 py-2 px-4 bg-green-600 text-white font-semibold text-center rounded-lg text-2xl shadow-md hover:bg-green-500 focus:outline-none focus:ring-2 focus:ring-green-400 focus:opacity-75 cursor-pointer">
                Login
            </router-link>
            <router-link to="/Register" class="w-full mr-1 py-2 px-4 bg-blue-600 text-white font-semibold text-center rounded-lg text-2xl shadow-md hover:bg-blue-500 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:opacity-75 cursor-pointer">
                Register
            </router-link>
        </div>
    </div>
    <div id="videoDarkOverlay">

    </div>
    <video autoplay muted loop id="myVideo">
        <source src="../../../public/concert.mp4" type="video/mp4">
    </video>
</template>

<script setup>

</script>

<style lang="scss">
    #CenterCallToAction{
        width: 100%;
        position:absolute;
        left:50%;
        top:50%;
        -webkit-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
    }

    #myVideo{
        width: 100vw;
        height: 100vh;
        object-fit: cover;
        position: fixed;
        left: 0;
        right: 0;
        top: 0;
        down: 0;
        z-index:-2;
    }

    #videoDarkOverlay{
        width: 100vw;
        height: 100vh;
        object-fit: cover;
        position: fixed;
        left: 0;
        right: 0;
        top: 0;
        down: 0;
        z-index:-1;
        background-color: rgba(0,0,0,0.65);
    }
</style>