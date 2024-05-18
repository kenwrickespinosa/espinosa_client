<template>
    <nav class="bg-gray-800 py-4">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between">
            <!-- Logo -->
                <div class="flex-shrink-0">
                    <NuxtLink to="/" class="text-white font-bold text-xl">ShoePee</NuxtLink>
                </div>

            <!-- Navigation Links -->
            <div class="hidden md:flex space-x-4">
                <NuxtLink to="/" class="text-white hover:text-gray-300">Home</NuxtLink>
                <NuxtLink to="/about" class="text-white hover:text-gray-300">About</NuxtLink>
                <NuxtLink to="/products" class="text-white hover:text-gray-300">Products</NuxtLink>
                <NuxtLink to="/contacts" class="text-white hover:text-gray-300">Contacts</NuxtLink>
            </div>
            </div>
         </div>
    </nav>

    <!-- Output the page content -->
    <div class="container mx-auto p-2">
        <slot />
    </div>
</template>