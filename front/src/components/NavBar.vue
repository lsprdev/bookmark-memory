<template>
    <span>
        <nav class="bg-[#000000] shadow-xl">
            <div class="max-w-6xl mx-auto px-4">

                <div class="flex justify-between">

                    <div>
                        <router-link to="/" class="flex items-center py-6 px-2">
                            <span class="text-white font-semibold text-xl tracking-tight px-2 font">BookMark Memory</span>
                        </router-link>
                    </div>

                    <div class="flex items-center py-4 px-2">
                        
                        <router-link class="py-2 px-6 font-semibold text-white rounded hover:bg-[#ffffff11] transition duration-300 mx-1" to="">
                            <span>Login</span>
                        </router-link>

                        <router-link class="py-2 px-6 font-semibold text-white rounded hover:bg-[#ffffff11] transition duration-300 mx-1" to="">
                            <span>Sign up</span>
                        </router-link>

                    </div>

                </div>

            </div>
        </nav>
    </span>
</template>