<template>
    <div>
        <div class="bg-gradient-to-r from-pink-500 to-yellow-500 h-screen w-full  rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 md ">
            <section class="h-screen">
                <div class="container px-6 py-12 h-full">
                    <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">
                        <div class="md:w-8/12 lg:w-6/12 mb-12 md:mb-0">
                            <img src="images/freework-removebg.png" />
                        </div>
                        <div class="md:w-8/12 lg:w-5/12 lg:ml-20">
                            <form>
                                <!-- Email input -->
                                <div class="mb-6">
                                    <input type="text"
                                        class="form-control block w-full px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                                        placeholder="Username" />
                                </div>
                                <div class="mb-6">
                                    <input type="text"
                                        class="form-control block w-full px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                                        placeholder="Email address" />
                                </div>
            
                                <!-- Password input -->
                                <div class="mb-6">
                                    <input type="password"
                                        class="form-control block w-full px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                                        placeholder="Password" />
                                </div>
                                <div class="mb-6">
                                    <input type="password"
                                        class="form-control block w-full px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                                        placeholder=" Confirm Password" />
                                </div>
                                
            
                                <div class="flex justify-between items-center mb-6">
                                    <div class="form-group form-check">
                                        <input type="checkbox"
                                            class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer"
                                            id="exampleCheck3" checked />
                                        <label class="form-check-label inline-block text-gray-800" for="exampleCheck2">Remember
                                            me</label>
                                    </div>
                                    <a href="#!"
                                        class="text-white hover:text-blue-700 focus:text-blue-700 active:text-blue-800 duration-200 transition ease-in-out">Forgot
                                        password?</a>
                                </div>
            
                                <!-- Submit button -->
                                <nuxt-link to="/"> 
                                    <button type="submit"
                                        class="inline-block px-7 py-3 bg-gradient-to-r from-green-400 to-blue-500  text-white font-medium text-sm leading-snug uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out w-full"
                                        data-mdb-ripple="true" data-mdb-ripple-color="light">
                                        Sign in
                                    </button>
                
                                    
                                </nuxt-link>
                
                                
                            </form>
                        </div>
                    </div>
                </div>
            </section>
            


            

            


        </div>


    </div>
</template>

<script>
export default {
    name: 'SignUp',
    layout: 'default',

    data() {
        return {
            timestamp: "",

        }
    },
    methods: {
        timeNow() {

        }

    }

}
</script>

<style>

</style>