<template>
    <div>
        <div>
            <div
                class="h-64 w-full  rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50  ">
                <nuxt-link to="/Home">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                        class="w-10 h-10 font-extrabold cursor-pointer">
                        <path
                            d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z" />
                    </svg>
                </nuxt-link>
                <div class="flex justify-around">

                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-12 h-12 font-extrabold mt-32">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
                        </svg>


                    </div>
                    <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
                        Hi, Ashbella
                    </h2>


                    <div class="bg-indigo-200 h-40 w-40 rounded-full mt-12">
                        <img src="images/lady.jpg" alt="PanCake" class="w-32 h-32 object-cover rounded-full mt-8" />
                    </div>
                </div>
            </div>

            <!------------start---new section---------->
            <div>
                <section class=" rounded-md ">
                    <div class="container">
            
                        <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">


                            <div class="md:w-8/12 lg:w-6/12  md:mb-0">
                                <img src="images/running.jpg" />
                            </div>
            
                            <div class="md:w-8/12 lg:w-5/12 lg:ml-20 ">
                                <h1 class=" text-3xl font-mono text-center rounded font-extrabold py-4 w-3/4 bg-red-300 mb-7"> LEG
                                    WORKOUTS</h1>
            
                                <div>
                                    <p class="w-5/6 font-serif leading-10  "> It is a long established fact that a reader will be
                                        distracted
                                        by
                                        the readable content of a page when looking at its
                                        layout. </p>
                                </div>
                            </div>
            
                            
                        </div>
            
                    </div>
                </section>
            </div>

            <!----------------endof running content 1--->

            <!--------start of final running content------->

            
            <!--------end of final running content--------->
            
        </div>
    </div>
</template>

<script>
export default {
    name: "Running",
    layout: "main"

};
</script>

<style>

</style>



