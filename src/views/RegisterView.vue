<template>
    <div id="Register">
        <div class="w-full p-6 flex justify-center items-center">
            <div class="w-full max-w-xs">            
                <div class="bg-black p-8 shadow rounded mb-6 px-4 py-3">
                    <h1 class="mb-6 mt-4 text-lg text-gray-300 font-thin">Let's start rocking</h1>
                    <div class="mb-4">
                        <label class="block mt-4 uppercase tracking-wide text-xs font-bold mb-2 text-gray-300">
                            First Name
                        </label>
                        <input 
                            type="text"
                            name="name"
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
                            email
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
                        <label class="block mt-4 uppercase tracking-wide text-xs font-bold mb-2 text-gray-300">
                            Confirm password
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
                    </div>
                    <span class="text-red-500">
                        This is an error message
                    </span>

                    <button type="submit" class="block w-full bg-green-600 text-white rounded-sm py-3 mb-4 text-sm tracking-wide">
                        Register
                    </button>
                </div>    
            
                <p class="text-center">
                    Already have an account?
                    <router-link to="/login" class="text-blue-500 no-underline hover:underline">
                        Login
                    </router-link>
                </p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>