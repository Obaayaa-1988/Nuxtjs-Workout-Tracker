<template>
    <div class="overflow-y-auto h-full">
        <div>
            <div
                class=" h-1/4 w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50">
                <div class="flex justify-around">
                    <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
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
                <div class="flex justify-center md:justify-end">

                </div>

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

            <section class="bg-gray-100 w-full h-3/4 pt-12 pb-40  md:col-span-2">
                <div>
                    <h3 class="text-xl font-semibold pt-12 font-mono pl-12">CARDIO TRAINING</h3>
                </div>
                <header>
                    <h3 class="text-xl font-semibold py-12 font-mono pl-12">Area Of Focus</h3>
                </header>

                <!----------------------start cardio cards-->
                <div class="flex justify-around px-12">
                    <nuxt-link to="/cardio">
                        <div class=" bg-white w-60 h-52 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer">
                            <div class="justify-center"> 
                                <div>
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 416 512 " class="w-20 h-20  fill-purple-600 ">
                                <path
                                    d="M272 96c26.51 0 48-21.49 48-48S298.51 0 272 0s-48 21.49-48 48 21.49 48 48 48zM113.69 317.47l-14.8 34.52H32c-17.67 0-32 14.33-32 32s14.33 32 32 32h77.45c19.25 0 36.58-11.44 44.11-29.09l8.79-20.52-10.67-6.3c-17.32-10.23-30.06-25.37-37.99-42.61zM384 223.99h-44.03l-26.06-53.25c-12.5-25.55-35.45-44.23-61.78-50.94l-71.08-21.14c-28.3-6.8-57.77-.55-80.84 17.14l-39.67 30.41c-14.03 10.75-16.69 30.83-5.92 44.86s30.84 16.66 44.86 5.92l39.69-30.41c7.67-5.89 17.44-8 25.27-6.14l14.7 4.37-37.46 87.39c-12.62 29.48-1.31 64.01 26.3 80.31l84.98 50.17-27.47 87.73c-5.28 16.86 4.11 34.81 20.97 40.09 3.19 1 6.41 1.48 9.58 1.48 13.61 0 26.23-8.77 30.52-22.45l31.64-101.06c5.91-20.77-2.89-43.08-21.64-54.39l-61.24-36.14 31.31-78.28 20.27 41.43c8 16.34 24.92 26.89 43.11 26.89H384c17.67 0 32-14.33 32-32s-14.33-31.99-32-31.99z" />
                            </svg>
                                </div>

                                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">RUNNING</div>

                            </div>
                           
                        </div>
                    </nuxt-link>
                <nuxt-link to="/cardio">
                    <div class=" bg-white w-60 h-52 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer ">
                        <div class="flex">
                            <div class="text-blue">hellooo</div>
                            <div class="text-blue-600 text-lg ml-4">hellooo</div>
                
                        </div>
                
                    </div>
                </nuxt-link>
                <nuxt-link to="/cardio">
                    <div class=" bg-white w-60 h-52 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer ">
                        <div class="flex">
                            <div class="text-blue">hellooo</div>
                            <div class="text-blue-600 text-lg ml-4">hellooo</div>
                
                        </div>
                
                    </div>
                </nuxt-link>

                <nuxt-link to="/cardio">
                    <div class=" bg-white w-60 h-52 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer">
                        <div class="flex">
                            <div class="text-blue">hellooo</div>
                            <div class="text-blue-600 text-lg ml-4">hellooo</div>
                
                        </div>
                
                    </div>
                </nuxt-link>


                    <!-- <nuxt-link to="/AbsWorkOut">
                        <div class=" bg-white rounded-3xl overflow-hidden shadow-md relative hover:shadow-l shadow-gray-500/50 cursor-pointer">
                            <div class="flex justify-center pt-16">
                                <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                            </div>
                            <div class="m-4">
                                <span class="font-semibold text-2xl font-mono">Abs</span>
                            </div>
                        </div>
                    </nuxt-link>


                    <nuxt-link to="/AbsWorkOut">
                        <div class=" bg-white rounded-3xl overflow-hidden shadow-md relative hover:shadow-l shadow-gray-500/50 cursor-pointer">
                            <div class="flex justify-center pt-16">
                                <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                            </div>
                            <div class="m-4">
                                <span class="font-semibold text-2xl font-mono">Abs</span>
                            </div>
                        </div>
                    </nuxt-link>

                    <nuxt-link to="/AbsWorkOut">
                        <div class=" bg-white rounded-3xl overflow-hidden shadow-md relative hover:shadow-l shadow-gray-500/50 cursor-pointer">
                            <div class="flex justify-center pt-16">
                                <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                            </div>
                            <div class="m-4">
                                <span class="font-semibold text-2xl font-mono">Abs</span>
                            </div>
                        </div>
                    </nuxt-link> -->

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