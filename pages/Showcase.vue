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
          <!-- rounded-br-full -->
          <!-- shadow-lg shadow-gray-500/50 -->
          

        ">
        <div class="flex justify-around mb:block">
            <div>
            <img src="images/work-remove.png" alt="PanCake" class="w-full h-full object-cover" />
          </div>

            
            <div> 

                <div> 
    
                    <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28 pb-12">
                      HELLO WELCOME TO MYFIT
                    </h2>
                </div>
              <div>
                <nuxt-link to="/" class="text-primary ml-2 rounded py-3 px-8  text-xl font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-blue-300 hover:text-white transition ease-out duration-500 bg-cyan-600 font-mono outline-none text-white" >Get Started</nuxt-link>
              </div>
            </div>

          
        </div>
      </div>

    
  </div>
</template>

<script>
export default {
    name: 'Showcase'

}
</script>

<style>

</style>