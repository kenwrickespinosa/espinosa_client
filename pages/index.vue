<template>
    <div class="flex items-center justify-center pl-5"> <!-- Adjusted left padding to pl-5 -->
        <div class="flex-1 mr-15">
            <h2 class="text-left m-2 text-4xl">Worry no more!<br><span class="text-red-500">ShoePee</span> have the shoes that you could trust.</h2>
            <div class="mt-5 space-x-5">
                <NuxtLink to="/login/signin" class="text-black border rounded-md p-2">Sign In</NuxtLink>
                <NuxtLink to="/login/signup" class="text-white bg-green-700 rounded-md p-2">Sign Up</NuxtLink>
            </div>
        </div>

        <div class="flex-shrink-0 m1 mt-5 pt-5 ml-5 flex justify-center"> <!-- Added justify-center to center the image -->
            <img src="/img/shoes_png.png" class="w-3/4 h-auto"/> <!-- Removed items-center -->
        </div>
    </div>
</template>

<script setup>

</script>