<template>
  <div>
      <div
        class=" h-1/4 w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50">
        <div class="flex justify-around">
          <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
            LEG WORKOUT
          </h2>
          <div></div>
      
          <div>
            <img src="images/legs.png" alt="PanCake" class="w-80 h-80 object-cover fill-blue-600" />
          </div>
        </div>
      </div>

      <section class="bg-gradient-to-r from-sky-500 to-indigo-500 w-full h-full px-16 py-6 md:col-span-2 ">
      
        <!--------start---------current date and stopwatch-->
        <div class="flex justify-center py-8">
          <h1 class="text-xl font-semibold pt-8 font-mono text-white" >LEG WORKOUT VARIATION</h1>
      
        </div>
      
        <!-----------------stopwatch end------->
      
        <!----------------------start cardio cards-->
        <div class="mt-8 pb-24 ">
          <nuxt-link to="/OneLegSquat">
            <div class="bg-white w-1/2 py-8 rounded overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer mb-8 mx-auto border-l-8 border-l-orange-500">
              <div class="flex justify-between">
                <div class="text-gray-600 ml-4 text-xl font-extrabold font-mono "> One Leg Squat</div>

                 <div >
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-cyan-600 mr-8">
                    <path
                      d="M500.5 231.4l-192-160C287.9 54.3 256 68.6 256 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2zm-256 0l-192-160C31.9 54.3 0 68.6 0 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2z" />
                  </svg>
                </div> 
      
              </div>
      
            </div>
          </nuxt-link>
      
      
          <nuxt-link to="/cardio">
            <div
              class="bg-white  w-1/2 py-8 rounded overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer  mb-8 mx-auto  border-l-8 border-l-yellow-500">
              <div class=" flex justify-between">
                <div class="text-gray-600 ml-4 text-xl font-extrabold font-mono ">Machine Leg Extentions</div>
                <div >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-cyan-600 mr-8" >
                  <path
                    d="M500.5 231.4l-192-160C287.9 54.3 256 68.6 256 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2zm-256 0l-192-160C31.9 54.3 0 68.6 0 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2z" />
                </svg>
                </div>
      
      
              </div>
      
            </div>
          </nuxt-link>
          <nuxt-link to="/LegPresses">
            <div
              class="bg-white w-1/2 py-8 rounded overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer mx-auto border-l-8 border-l-green-500">
              <div class=" flex justify-between">
                <div class="text-gray-600 ml-4 text-xl font-extrabold font-mono ">Leg Presses</div>
                <div>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-cyan-600 mr-8">
                  <path
                    d="M500.5 231.4l-192-160C287.9 54.3 256 68.6 256 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2zm-256 0l-192-160C31.9 54.3 0 68.6 0 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2z" />
                </svg>
                </div>
      
      
              </div>
            </div>
          </nuxt-link>
      
        </div>
      
        <!-------------end cardio cards only-->
      
      </section>



      




    
  </div>
</template>

<script>
export default {
    name: 'LegWorkOut',
    layout:"main"


}
</script>


<style>

</style>