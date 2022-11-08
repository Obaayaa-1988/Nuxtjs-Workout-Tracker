<template>
    <div>

        <div class="
          h-screen
          w-full
          bg-indigo-200
          rounded-md
          bg-clip-padding
          backdrop-filter backdrop-blur-sm
          bg-opacity-40
          border border-gray-100
          md
          

        ">
            <div class="flex justify-around mb:block">
                <div>
                    <img src="images/removebg.png" alt="PanCake" class="w-full h-full object-cover" />
                </div>


                <div>
                    <div>
                        <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28 pb-20">
                            WELCOME TO MYFIT
                        </h2>
                    </div>
                    <div>
                        <nuxt-link to="/"
                            class="text-primary ml-2 rounded py-4 px-10  text-xl font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-blue-300 hover:text-white transition ease-out duration-500 bg-pink-600 font-mono outline-none text-white">
                            Get Started</nuxt-link>
                    </div>

                </div>

                <!------------------------sign up buttons section-->
            </div>

            <div >
                <div class="text-center">
                    <nuxt-link to="/"
                        class="text-primary ml-2 rounded-lg py-5 px-32  text-xl font-bold cursor-pointer tracking-wider border-primary md:border-2  hover:text-black transition ease-out duration-500 font-mono outline-none bg-white mb-8">
                        Log In With Google</nuxt-link>
                </div>
                <br>
                <br>
                <br>
                <div class="text-center" >
                    <nuxt-link to="/"
                        class="text-primary ml-2 rounded-lg py-5 px-28  text-xl  cursor-pointer tracking-wider border-primary md:border-2 hover:bg-blue-300 hover:text-white transition ease-out duration-500 bg-black font-mono outline-none text-white">
                        Log In With FaceBook</nuxt-link>
                </div>
            
            </div>



        </div>


    </div>
</template>

<script>
export default {
    name: 'Showcase',

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