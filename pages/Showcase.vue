<template>
    <div>
        <div class=" h-screen w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 md ">
            <div class="flex justify-around mb:block">
                <div>
                    <img src="images/freework-removebg.png" alt="PanCake" class="w-full h-full object-cover" />
                </div>


                <div>
                    <div>
                        <h2 class="text-neutral-700 text-5xl font-extrabold font-mono mt-48 pb-20">
                            WELCOME TO MYFIT APP
                        </h2>
                    </div>

                </div>

                <!------------------------sign up buttons section-->
            </div>

            <div class="mt-10">
                <div class="text-center">
                    <nuxt-link to="/"
                        class="text-primary ml-2 rounded-lg py-5 px-32  text-xl font-bold cursor-pointer tracking-wider border-primary md:border-2  hover:text-black transition ease-out duration-500 font-mono outline-none bg-pink-600 mb-8">
                        Log In With Google</nuxt-link>
                </div>
                <br>
                <br>
                <br>
                <div class="text-center" >
                    <nuxt-link to="/"
                        class="text-primary ml-2 rounded-lg py-5 px-28  text-xl  cursor-pointer tracking-wider border-primary md:border-2 hover:bg-black hover:text-white transition ease-out duration-500 bg-blue-300 font-mono outline-none text-white">
                        Log In With FaceBook</nuxt-link>
                </div>
                <br>
                <br>
                <div class="text-center" >
                     <span >
                        Not A User?<nuxt-link to="/" class="text-cyan-500"> Sign Up</nuxt-link>
                    </span>
                </div>
            
            </div>



        </div>


    </div>
</template>

<script>
export default {
    name: 'Showcase',
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