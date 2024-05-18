<template>
    <nav class="bg-gray-800 py-4">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between">
            <!-- Logo -->
                <div class="flex-shrink-0">
                    <NuxtLink to="/" class="text-white font-bold text-xl">ShoePee</NuxtLink>
                </div>
            </div>
         </div>
    </nav>

    <div>
        <slot />
    </div>
</template>

<script setup>

</script>