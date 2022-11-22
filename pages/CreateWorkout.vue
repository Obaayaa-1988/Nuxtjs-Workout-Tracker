<template>
    <div>
        <div
            class="bg-gradient-to-r from-sky-500 to-indigo-500 h-screen w-full  rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 md ">
            <section class="h-screen">
                <div class="container px-6 py-12 h-full">
                    <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">
                        <div class="md:w-8/12 lg:w-6/12 mb-12 md:mb-0">
                            <img src="images/work-create-remove.png" />
                        </div>
                        <div class="md:w-8/12 lg:w-5/12 lg:ml-20">
                            <form class="bg-gray-100 py-10 px-10 rounded text-lg">
                                <h1 class="text-center py-4 font-extrabold font-mono"> Create A Workout</h1>

                                <!-- Email input -->
                                <div class="mb-6">
                                    <label class="font-bold font-mono">Exercise Name</label>
                                    <input type="text"
                                        class="form-control block w-1/2 px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" />
                                </div>
                                <div class="mb-6">
                                    <label class="font-bold font-mono">Sets</label>
                                    <input type="text"
                                        class="form-control block w-1/2 px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" />
                                </div>

                                <!-- Password input -->
                                <div class="mb-6">
                                    <label class="font-bold font-mono">Repititions</label>
                                    <input type="password"
                                        class="form-control block w-1/2 px-4 py-2 text-xl font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" />
                                </div>


                                <!-- Submit button -->
                                <nuxt-link to="/">
                                    <button type="submit"
                                        class="inline-block py-3 bg-gradient-to-r from-green-400 to-blue-500  text-white font-medium text-sm leading-snug  rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out w-1/2"
                                        data-mdb-ripple="true" data-mdb-ripple-color="light">
                                        Add A Workout
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
    name: "NavigateWorkout",
    layout: "main"

}
</script>

<style>

</style>