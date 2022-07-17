<template>
    <span>
        <nav>
            <div class="max-w-7xl mx-auto">

                <div class="flex justify-between">

                    <div>
                        <router-link to="/" class="flex items-center py-3 px-2">
                            <span class="text-black font-semibold text-xl tracking-tight font">BookMark Memory</span>
                        </router-link>
                    </div>

                    <div class="flex items-center py-4 px-2">
                        
                        <router-link class="px-6 font-semibold text-black rounded hover:bg-blue-200 transition duration-300 mx-1" to="">
                            <span>Login</span>
                        </router-link>

                        <router-link class="px-6 font-semibold text-black rounded hover:bg-blue-200 transition duration-300 mx-1" to="">
                            <span>Sign up</span>
                        </router-link>

                    </div>

                </div>

            </div>
        </nav>
    </span>
</template>