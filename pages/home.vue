<template>
    <div class="overflow-y-auto h-full">
        <div>
            <div class=" h-1/4 w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50">
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
                            <div class="
                  bg-lime-300
                  rounded-3xl
                  overflow-hidden
                  shadow-md
                  relative
                  hover:shadow-lg
                  shadow-gray-500/50
                  cursor-pointer
                ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Abs</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/GluteWorkOut">

                            <div class="
                  bg-pink-500
                  rounded-3xl
                  overflow-hidden
                  shadow-gray-500/50
                  shadow-md
                  relative
                  hover:shadow-lg
                  cursor-pointer
                ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/glutes.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Glutes</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/ChestWorkOut">

                            <div class="
                  bg-teal-400
                  rounded-3xl
                  overflow-hidden
                  shadow-md
                  relative
                  hover:shadow-lg
                  shadow-gray-500/50
                  cursor-pointer
                ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/chest.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Chest</span>

                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/ArmsWorkOut">

                            <div class="
                  bg-yellow-300
                  rounded-3xl
                  overflow-hidden
                  shadow-md
                  relative
                  hover:shadow-lg
                  shadow-gray-500/50
                  cursor-pointer
                ">
                                <div class="flex justify-center pt-16">
                                    <img src="images/arms.png" alt="PanCake" class="w-36 h-36 object-cover" />
                                </div>
                                <div class="m-4">
                                    <span class="font-semibold text-2xl font-mono">Arms</span>
                                </div>
                            </div>
                        </nuxt-link>

                        <nuxt-link to="/FullWorkOut">


                            <div class="
                  bg-cyan-600
                  rounded-3xl
                  overflow-hidden
                  shadow-md
                  relative
                  hover:shadow-lg
                  shadow-gray-500/50
                  cursor-pointer
                ">
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