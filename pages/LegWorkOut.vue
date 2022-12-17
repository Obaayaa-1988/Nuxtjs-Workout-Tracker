<template>
  <div>
    <div
      class=" h-1/4 w-full bg-indigo-300 rounded-b-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50">
      <nuxt-link to="/Home">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-10 h-10 font-extrabold cursor-pointer">
          <path
            d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z" />
        </svg>
      </nuxt-link>
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

    <div>
      <section class=" rounded-md ">
        <div class="container">

          <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">

            <div class="md:w-8/12 lg:w-5/12 lg:ml-20 ">
              <h1 class=" text-3xl font-mono text-center rounded font-extrabold py-4 w-3/4 bg-red-300 mb-7"> LEG
                WORKOUTS</h1>

              <div>
                <p class="w-5/6 font-serif leading-10  "> It is a long established fact that a reader will be distracted
                  by
                  the readable content of a page when looking at its
                  layout. </p>
              </div>
            </div>

            <div class="md:w-8/12 lg:w-6/12  md:mb-0">
              <img src="images/legwork.jpg" />
            </div>
          </div>

        </div>
      </section>
    </div>

    <section class="bg-sky-100 rounded-t-3xl w-full h-full px-16 py-6 md:col-span-2  ">

      <!--------start---------current date and stopwatch-->
      <div class="flex justify-center py-8">
        <h1 class="text-3xl font-extrabold pt-8 font-mono ">LEG WORKOUT VARIATION</h1>

      </div>

      <!-----------------stopwatch end------->

      <!----------------------start cardio cards-->
      <div class="mt-8 pb-24 ">
        <nuxt-link to="/OneLegSquat">
          <div
            class="bg-yellow-300  w-2/3 py-8 overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer mb-8 mx-auto border-l-8 border-l-orange-500">
            <div class="flex justify-between">
              <div class=" ml-4 text-xl font-extrabold font-mono text-white"> Bench Press</div>

              <div>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-white mr-8">
                  <path
                    d="M500.5 231.4l-192-160C287.9 54.3 256 68.6 256 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2zm-256 0l-192-160C31.9 54.3 0 68.6 0 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2z" />
                </svg>
              </div>

            </div>

          </div>
        </nuxt-link>


        <nuxt-link to="/OneLegSquat">
          <div
            class="bg-cyan-400  w-2/3 py-8 rounded overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer  mb-8 mx-auto border-l-8 border-l-orange-500">
            <div class=" flex justify-between">
              <div class="text-white ml-4 text-xl font-extrabold font-mono ">One Leg Squat</div>
              <div>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-white mr-8">
                  <path
                    d="M500.5 231.4l-192-160C287.9 54.3 256 68.6 256 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2zm-256 0l-192-160C31.9 54.3 0 68.6 0 96v320c0 27.4 31.9 41.8 52.5 24.6l192-160c15.3-12.8 15.3-36.4 0-49.2z" />
                </svg>
              </div>


            </div>

          </div>
        </nuxt-link>
        <nuxt-link to="/LegPresses">
          <div
            class="bg-emerald-300  w-2/3 py-8 rounded overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer mx-auto border-l-8 border-l-orange-500 ">
            <div class=" flex justify-between">
              <div class="text-white ml-4 text-xl font-extrabold font-mono ">Leg Extension</div>
              <div>
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-8 h-8 fill-white mr-8">
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
  layout: "main"


}
</script>


<style>

</style>