<template>
    <div class="overflow-y-auto h-full">
        <div>
            <div
                class=" h-1/4 w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50">
                <div class="flex justify-around">
                    <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-44">
                        CHOOSE A WORKOUT
                    </h2>
                    <div></div>

                    <div>
                        <img src="images/removebg.png" alt="PanCake" class="w-96 h-96 object-cover" />
                    </div>
                </div>
            </div>

            <!---------start of second main section-->

            <main class="px-16 py-6 md:col-span-2">
                <div>
                    <h3 class="text-xl font-semibold pt-12 font-mono">WEIGTH TRAINING</h3>
                </div>
                <header>
                    <h3 class="text-xl font-semibold pt-12 font-mono">Area Of Focus</h3>
                </header>

                <div>
                    <div class="mt-8 grid lg:grid-cols-3 gap-10">
                        <!---cards here-->

                        <nuxt-link to="/LegWorkOut">
                            <div class="bg-red-200 rounded-3xl cursor-pointer shadow-lg shadow-gray-500/50 ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/legs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Legs</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/AbsWorkOut">
                            <div class=" bg-lime-300 rounded-3xl overflow-hidden shadow-md relative hover:shadow-l shadow-gray-500/50 cursor-pointer">
                                <div class="flex justify-center pt-16">
                                    <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Abs</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/GluteWorkOut">

                            <div class=" bg-pink-500 rounded-3xl overflow-hidden shadow-gray-500/50 shadow-md relative hover:shadow-lg cursor-pointer ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/glutes.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Glutes</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/ChestWorkOut">
                            <div class=" bg-teal-400 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lgshadow-gray-500/50 cursor-pointer">
                                <div class="flex justify-center pt-16">
                                    <img src="images/chest.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Chest</span>

                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/ArmsWorkOut">
                            <div class=" bg-yellow-300 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer">
                                <div class="flex justify-center pt-16">
                                    <img src="images/arms.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Arms</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/FullWorkOut">
                            <div class=" bg-cyan-600 rounded-3xl overflow-hidd shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer">
                                <div class="flex justify-center pt-16">
                                    <img src="images/full.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Full Body</span>
                                </div>
                            </div>
                        </nuxt-link>

                    </div>
                </div>

            </main>

            <section class="bg-gray-100 w-full h-3/4  px-16 py-6 md:col-span-2 ">
                <div>
                    <h3 class="text-xl font-semibold pt-12 font-mono">CARDIO TRAINING</h3>
                </div>
                <header>
                    <h3 class="text-xl font-semibold py-12 font-mono ">Area Of Focus</h3>
                </header>

                <!----------------------start cardio cards-->
                <div class="mt-8 grid lg:grid-cols-3 gap-10 px-12 pb-24">
                    <nuxt-link to="/cardio">
                        <div class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500  w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
                            <div > 
                                <div class="mx-auto" >
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 416 512 " class="w-28 h-28  fill-white ">
                                <path
                                    d="M272 96c26.51 0 48-21.49 48-48S298.51 0 272 0s-48 21.49-48 48 21.49 48 48 48zM113.69 317.47l-14.8 34.52H32c-17.67 0-32 14.33-32 32s14.33 32 32 32h77.45c19.25 0 36.58-11.44 44.11-29.09l8.79-20.52-10.67-6.3c-17.32-10.23-30.06-25.37-37.99-42.61zM384 223.99h-44.03l-26.06-53.25c-12.5-25.55-35.45-44.23-61.78-50.94l-71.08-21.14c-28.3-6.8-57.77-.55-80.84 17.14l-39.67 30.41c-14.03 10.75-16.69 30.83-5.92 44.86s30.84 16.66 44.86 5.92l39.69-30.41c7.67-5.89 17.44-8 25.27-6.14l14.7 4.37-37.46 87.39c-12.62 29.48-1.31 64.01 26.3 80.31l84.98 50.17-27.47 87.73c-5.28 16.86 4.11 34.81 20.97 40.09 3.19 1 6.41 1.48 9.58 1.48 13.61 0 26.23-8.77 30.52-22.45l31.64-101.06c5.91-20.77-2.89-43.08-21.64-54.39l-61.24-36.14 31.31-78.28 20.27 41.43c8 16.34 24.92 26.89 43.11 26.89H384c17.67 0 32-14.33 32-32s-14.33-31.99-32-31.99z" />
                            </svg>
                                </div>

                                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4 text-white">RUNNING</div>

                            </div>
                           
                        </div>
                    </nuxt-link>
                    

                   <nuxt-link to="/cardio">
                    <div class=" bg-gradient-to-r from-green-400 to-blue-500 w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
                        <div class="justify-center">
                            <div>
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" class="w-28 h-28  fill-white " >
                                <path
                                    d="M400 96a48 48 0 1 0-48-48 48 48 0 0 0 48 48zm-4 121a31.9 31.9 0 0 0 20 7h64a32 32 0 0 0 0-64h-52.78L356 103a31.94 31.94 0 0 0-40.81.68l-112 96a32 32 0 0 0 3.08 50.92L288 305.12V416a32 32 0 0 0 64 0V288a32 32 0 0 0-14.25-26.62l-41.36-27.57 58.25-49.92zm116 39a128 128 0 1 0 128 128 128 128 0 0 0-128-128zm0 192a64 64 0 1 1 64-64 64 64 0 0 1-64 64zM128 256a128 128 0 1 0 128 128 128 128 0 0 0-128-128zm0 192a64 64 0 1 1 64-64 64 64 0 0 1-64 64z" />
                            </svg>
                            </div>
                        
                            <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4 text-white">CYCLING</div>
                        
                        </div>
                
                    </div>
                </nuxt-link>
                <nuxt-link to="/cardio">
                    <div class="bg-gradient-to-r from-pink-500 to-yellow-500    w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
                        <div class="justify-center">
                            <div>
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" class="w-28 h-28  fill-white " >
                                    <path
                                        d="M208 96c26.5 0 48-21.5 48-48S234.5 0 208 0s-48 21.5-48 48 21.5 48 48 48zm94.5 149.1l-23.3-11.8-9.7-29.4c-14.7-44.6-55.7-75.8-102.2-75.9-36-.1-55.9 10.1-93.3 25.2-21.6 8.7-39.3 25.2-49.7 46.2L17.6 213c-7.8 15.8-1.5 35 14.2 42.9 15.6 7.9 34.6 1.5 42.5-14.3L81 228c3.5-7 9.3-12.5 16.5-15.4l26.8-10.8-15.2 60.7c-5.2 20.8.4 42.9 14.9 58.8l59.9 65.4c7.2 7.9 12.3 17.4 14.9 27.7l18.3 73.3c4.3 17.1 21.7 27.6 38.8 23.3 17.1-4.3 27.6-21.7 23.3-38.8l-22.2-89c-2.6-10.3-7.7-19.9-14.9-27.7l-45.5-49.7 17.2-68.7 5.5 16.5c5.3 16.1 16.7 29.4 31.7 37l23.3 11.8c15.6 7.9 34.6 1.5 42.5-14.3 7.7-15.7 1.4-35.1-14.3-43zM73.6 385.8c-3.2 8.1-8 15.4-14.2 21.5l-50 50.1c-12.5 12.5-12.5 32.8 0 45.3s32.7 12.5 45.2 0l59.4-59.4c6.1-6.1 10.9-13.4 14.2-21.5l13.5-33.8c-55.3-60.3-38.7-41.8-47.4-53.7l-20.7 51.5z" />
                                </svg>
                            </div>
                        
                            <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4 text-white">WALKING</div>
                        
                        </div>
                    </div>
                </nuxt-link>
                   
                </div>

                <!-------------end cardio cards only-->

            </section>
        </div>
    </div>
</template>

<script>
export default {
    name: "HomePage",
    layout: "main"

};
</script>

<style>

</style>