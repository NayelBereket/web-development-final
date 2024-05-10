<template>
    <header class="bg-gull-gray-800 py-2">
        <main class="container mx-auto flex w-full items-center justify-between py-4 px-6">
            <div class="flex items-center"> <!-- Changed from text-white to flex and items-center -->
                <!-- img src="/Users/lenovo/Downloads/Asset 7.png" alt="Skilled Strings Logo" class="h-8 mr-2" -- > <-- Replace "/path/to/your/image.png" with the actual path to your image -->
                <nav>
                    <div class="w-full text-center text-xl font-extrabold sm:w-fit sm:text-left">
                        <nuxt-link to="/"> 
                            <span class="text-buttercup-500 hover:text-buttercup-400 ">Skilled</span>
                            <span class="dark:text-white">Strings</span>
                        </nuxt-link>
                    </div>
                        <nuxt-link to="/">
                    <div class="text-center text-sm text-white gap-1">Easy Way to learn Guitar</div>
                        </nuxt-link>
                </nav> 
            </div>
                
            <nav class="text-gull-gray-200 text-md flex flex-row justify-end gap-4">
                <!--nuxt-link to="/"> Home </nuxt-link-->
                <nuxt-link to="/page1" class="text-gull-gray-200 hover:text-buttercup-500"> About Us </nuxt-link>
                <nuxt-link to="/page2" class="text-gull-gray-200 hover:text-buttercup-500"> Contact US </nuxt-link>
                <nuxt-link to="/page3" class="text-gull-gray-200 hover:text-buttercup-500"> Our Services </nuxt-link>
                <nuxt-link to="/page4" class="text-gull-gray-200 hover:text-buttercup-500"> Blog </nuxt-link>
                <nuxt-link to="/page5" class="text-gull-gray-200 hover:text-buttercup-500"> Our Instructors </nuxt-link>
            </nav>
        </main>
    </header>
</template>
