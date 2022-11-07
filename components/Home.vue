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
                    <div class="bg-red-200 rounded-3xl  cursor-pointer">
                      <div class="flex justify-center pt-16"> 
                        <img src="images/legs.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Legs</span>
                            <!-- <span class="block text-gray-500 text-sm">See Variations</span> -->
                        </div>
                        
                    </div>

                    <div class="bg-lime-300 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <div class="flex justify-center pt-16"> 
                        <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Abs</span>
                           
                        </div>
                        
                    </div>


                    <div class="bg-purple-200 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <div class="flex justify-center pt-16"> 
                        <img src="images/glutes.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Glutes</span>
                        </div>
                        
                    </div>

                    <div class="bg-teal-400 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                        <div class="flex justify-center pt-16"> 
                        <img src="images/chest.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Chest</span>
                            <!-- <span class="block text-gray-500 text-sm">See Variations</span> -->
                        </div>
                       
                    </div>


                    <div class="bg-blue-200 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer ">
                        <div class="flex justify-center pt-16"> 
                        <img src="images/arms.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Arms</span>
                            
                        </div>
                       
                    </div>


                    <div class="bg-cyan-600 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                      <div class="flex justify-center pt-16"> 
                        <img src="images/full.png" alt="PanCake" class="w-36 h-36 object-cover">

                      </div>
                        <div class="m-4">
                            <span class="font-semibold text-2xl font-mono">Full Body</span>
                            
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