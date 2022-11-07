<template>
  <div class="flex min-h-screen">
    <div>
      <Navigation />
    </div> 

     <div class="flex-1">
      <main class="px-16 py-6 bg-gray-100 md:col-span-2">
            <div class="flex justify-center md:justify-end">
                <!-- <a href="#"
                    class="text-primary rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-primary hover:text-white transition ease-out duration-500">Log
                    In</a> -->
                <a href="#"
                    class="text-primary ml-2 rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider border-primary md:border-2 hover:bg-primary hover:text-white transition ease-out duration-500  ">Sign
                    Out</a>
            </div>

            <header>
                <h2 class="text-gray-700 text-4xl font-semibold">CHOOSE A WORKOUT </h2>
                <h3 class="text-xl font-semibold pt-12 ">Area Of Focus </h3>
            </header>

            <div>

                <div class="mt-8  grid lg:grid-cols-3 gap-10 ">
                    <!---cards here-->
                    <div class="bg-red-200 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <img src="/images/cake1.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Legs</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                        
                    </div>

                    <div class="bg-lime-300 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <img src="/images/cake1.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Glutes</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                        
                    </div>


                    <div class="bg-purple-200 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <img src="/images/cake1.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Abs</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                        
                    </div>

                    <div class="bg-blue-200 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <img src="/images/cake1.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Chest</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                       
                    </div>


                    <div class="bg-yellow-300 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer ">
                        <img src="/images/cake2.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Arms</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                       
                    </div>


                    <div class="bg-cyan-600 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <img src="/images/cake3.jpg" alt="PanCake" class="w-full h-32 sm:h-48 object-cover">
                        <div class="m-4">
                            <span class="font-bold">Full Body</span>
                            <span class="block text-gray-500 text-sm">See Variations</span>
                        </div>
                       
                    </div>
                </div>

            </div>
            <div class="pt-20"> 

              <FooterTracker />
            </div>

        </main>
      
      </div>     
     
  </div>


</template>

<script>
export default {
  name: "Home",
  // components: { FooterTracker }
};
</script>

<style>
</style>