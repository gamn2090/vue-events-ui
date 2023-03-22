<template>
    <div id="Register">
        <div class="w-full p-6 flex justify-center items-center">
            <div class="w-full max-w-xs">            
                <div class="bg-black p-8 shadow rounded mb-6 px-4 py-3">
                    <h1 class="mb-6 mt-4 text-lg text-gray-300 font-thin">Let's get rocking</h1>
                    <div class="mb-4">
                        <label class="block uppercase tracking-wide text-xs font-bold mb-2 text-gray-300">
                            Email
                        </label>
                        <input 
                            type="text" 
                            class="
                                appearance-none
                                block
                                w-full
                                bg-white
                                text-gray-700
                                border
                                border-gray-400
                                rounded
                                px-4
                                py-3
                                leading-tight
                                focus:outline-none
                                focus:bg-white
                                focus:border-gray-500">
                        <label class="block mt-4 uppercase tracking-wide text-xs font-bold mb-2 text-gray-300">
                            Password
                        </label>
                        <input 
                            type="password" 
                            class="
                                appearance-none
                                block
                                w-full
                                bg-white
                                text-gray-700
                                border
                                border-gray-400
                                rounded
                                px-4
                                py-3
                                leading-tight
                                focus:outline-none
                                focus:bg-white
                                focus:border-gray-500">
                    </div>
                    <span class="text-red-500">
                        This is an error message
                    </span>

                    <button type="submit" class="block w-full bg-green-600 text-white rounded-sm py-3 mb-4 text-sm tracking-wide">
                        Login
                    </button>
                </div>    
            
                <p class="text-center">
                    Don't have an account yet?
                    <router-link to="/register" class="text-blue-500 no-underline hover:underline">
                        Register
                    </router-link>
                </p>
            </div>
        </div>
    </div>
</template>