<template>
  <div>
    <div>
      <div
        class="h-64 w-full  rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50  ">
        <div class="flex justify-around">

          <div>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-12 h-12 font-extrabold mt-32">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
            </svg>


          </div>
          <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
            Hi, Ashbella
          </h2>


          <div class="bg-indigo-200 h-40 w-40 rounded-full mt-12">
            <img src="images/lady.jpg" alt="PanCake" class="w-32 h-32 object-cover rounded-full mt-8" />
          </div>
        </div>
      </div>

      <!------------start---new section-->

      <section class="bg-gradient-to-r from-green-400 to-blue-500 w-full h-full rounded-b-3xl  px-16 py-6 md:col-span-2 ">

        <!--------start---------current date and stopwatch-->
        <div class="flex justify-center py-20">
          <!-- <div class="text-white text-2xl">11th November 2022</div> -->

          <div class="bg-white w-60 h-60 rounded-full border-gray-100 border-8"> 
            <!-- <p class="font-extrabold">9:46</p> -->

          </div>


        </div>

        <!-----------------stopwatch end------->
       
        <!----------------------start cardio cards-->
        <div class="mt-8 grid lg:grid-cols-3 gap-10 px-12 pb-24">

          <nuxt-link to="/PickCalender">
            <div
              class="bg-white   w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
              <div class="justify-center">
                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">Pick Calender</div>
                <div class="pl-28 pt-8">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-16 h-16 fill-purple-600">
                    <path
                      d="M400 64h-48V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H160V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zm-6 400H54c-3.3 0-6-2.7-6-6V160h352v298c0 3.3-2.7 6-6 6z" />
                  </svg>
                </div>
          
          
              </div>
            </div>
          </nuxt-link>

          <nuxt-link to="/WorkoutGoal">
            <div
              class="bg-white  w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
              <div class="justify-center">
                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">Set Workout Goals</div>
                <div class="pl-28 pt-8">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" class="w-16 h-16 fill-lime-400">
                    <path
                      d="M104 96H56c-13.3 0-24 10.7-24 24v104H8c-4.4 0-8 3.6-8 8v48c0 4.4 3.6 8 8 8h24v104c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V120c0-13.3-10.7-24-24-24zm528 128h-24V120c0-13.3-10.7-24-24-24h-48c-13.3 0-24 10.7-24 24v272c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V288h24c4.4 0 8-3.6 8-8v-48c0-4.4-3.6-8-8-8zM456 32h-48c-13.3 0-24 10.7-24 24v168H256V56c0-13.3-10.7-24-24-24h-48c-13.3 0-24 10.7-24 24v400c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V288h128v168c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V56c0-13.3-10.7-24-24-24z" />
                  </svg>
          
                </div>
          
          
              </div>
          
            </div>
          </nuxt-link>
          <nuxt-link to="/CreateWorkout">
            <div class="bg-white   w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
              <div >
                
                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">Create A Workout</div>
                <div class="pl-28 pt-8" >
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-16 h-16 fill-pink-500">
                  <path
                    d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" />
                </svg>
                </div>
      
              </div>
      
            </div>
          </nuxt-link>
      
      
          
          
      
        </div>
        </section>

        <!---------------------added workouts section------->
        <div>
          <section class="h-screen">
            <div class="container px-6 h-full">  
              <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">
                <div class="md:w-8/12 lg:w-6/12 mb-12 md:mb-0">
                  <img src="images/work-create-remove.png" />
                </div>
                <div class="md:w-8/12 lg:w-5/12 lg:ml-20">
                
                   <!-- <div>
                    <h1 class=" text-2xl font-mono font-extrabold text-center">Recently Added Workouts</h1>
                  </div>  -->
                  <div
                    class="flex justify-between bg-purple-300 w-full py-5 rounded overflow-hidden shadow-md hover:shadow-lg shadow-gray-500/50  mb-8 mx-auto ">
                    <div class="text-white ml-4 text-xl font-extrabold font-mono "> Hip Thrust </div>
                  
                    <div class="text-white text-xl font-extrabold font-mono ">
                      <p> 3 Sets </p>
                    </div>
                    <div class="text-white text-xl font-extrabold font-mono ">
                      <p> 6 Reps </p>
                    </div>
                    <div class="text-white  text-xl font-extrabold font-mono ">
                      <p> 60 Seconds rest </p>
                    </div>
                  
                    <div>
                      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-6 h-6 fill-red-500 mr-4 cursor-pointer">
                        <path
                          d="M432 32H312l-9.4-18.7A24 24 0 0 0 281.1 0H166.8a23.72 23.72 0 0 0-21.4 13.3L136 32H16A16 16 0 0 0 0 48v32a16 16 0 0 0 16 16h416a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16zM53.2 467a48 48 0 0 0 47.9 45h245.8a48 48 0 0 0 47.9-45L416 128H32z" />
                      </svg>
                    </div>
                  
                  </div>
                  
                </div>
              </div>
            </div>
          </section>    
        </div>


      <!----------workout goal section-->

      <section class="bg-gray-100 w-full h-full  px-16 py-6 md:col-span-2 "> 
        <div class="flex justify-center font-mono text-4xl  font-extrabold">
                    <h2> MY GOALS</h2>
                  </div>

        <!-------------------------------Daily Goals ----section-->
        <div class="mt-8 grid lg:grid-cols-3  gap-10 px-12 pb-24 mx-auto">
          <div
            class="bg-cyan-200   w-56 h-60 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
            <div>
              <div class="text-blue ml-4 text-3xl font-extrabold font-mono pt-4">Kcal </div>
              <div class=" pt-8">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-16 h-16 fill-pink-500">
                  <path
                    d="M159.3 5.4c7.8-7.3 19.9-7.2 27.7 .1c27.6 25.9 53.5 53.8 77.7 84c11-14.4 23.5-30.1 37-42.9c7.9-7.4 20.1-7.4 28 .1c34.6 33 63.9 76.6 84.5 118c20.3 40.8 33.8 82.5 33.8 111.9C448 404.2 348.2 512 224 512C98.4 512 0 404.1 0 276.5c0-38.4 17.8-85.3 45.4-131.7C73.3 97.7 112.7 48.6 159.3 5.4zM225.7 416c25.3 0 47.7-7 68.8-21c42.1-29.4 53.4-88.2 28.1-134.4c-2.8-5.6-5.6-11.2-9.8-16.8l-50.6 58.8s-81.4-103.6-87.1-110.6C133.1 243.8 112 273.2 112 306.8C112 375.4 162.6 416 225.7 416z" />
                </svg>

                <h1 class="text-xl  pl-12">1500</h1>
              </div>
        
            </div>
        
          </div>
        
        
          <div
            class="bg-purple-200  w-56 h-60 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
            <div class="justify-center">
              <div class="text-blue ml-4 text-3xl font-extrabold font-mono pt-4">Weight</div>
              <div class=" pt-8">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" class="w-16 h-16 fill-pink-500">
                  <path
                    d="M208 48c0 26.5-21.5 48-48 48s-48-21.5-48-48s21.5-48 48-48s48 21.5 48 48zM152 352V480c0 17.7-14.3 32-32 32s-32-14.3-32-32V256.9L59.4 304.5c-9.1 15.1-28.8 20-43.9 10.9s-20-28.8-10.9-43.9l58.3-97c17.4-28.9 48.6-46.6 82.3-46.6h29.7c33.7 0 64.9 17.7 82.3 46.6l58.3 97c9.1 15.1 4.2 34.8-10.9 43.9s-34.8 4.2-43.9-10.9L232 256.9V480c0 17.7-14.3 32-32 32s-32-14.3-32-32V352H152z" />
                </svg>
                <h1 class="text-xl  pl-12">56KG</h1>
        
              </div>
        
        
            </div>
        
          </div>
        
          <div
            class="bg-orange-200   w-56 h-60 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
            <div class="justify-center">
              <div class="text-blue ml-4 text-3xl font-extrabold font-mono pt-4">Sleep</div>
              <div class=" pt-8">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" class="w-16 h-16 fill-pink-500">
                <path
                  d="M32 32c17.7 0 32 14.3 32 32V320H288V160c0-17.7 14.3-32 32-32H544c53 0 96 43 96 96V448c0 17.7-14.3 32-32 32s-32-14.3-32-32V416H352 320 64v32c0 17.7-14.3 32-32 32s-32-14.3-32-32V64C0 46.3 14.3 32 32 32zM176 288c-44.2 0-80-35.8-80-80s35.8-80 80-80s80 35.8 80 80s-35.8 80-80 80z" />
              </svg>
              <h1 class="text-xl  pl-12"> 7 HRS</h1>
              </div>
        
        
            </div>
          </div>
        
        
        
          <div
            class="bg-yellow-200   w-56 h-60 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
            <div class="justify-center">
              <div class="text-blue ml-4 text-3xl font-extrabold font-mono pt-4">Water</div>
              <div class=" pt-8">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 512" class="w-16 h-16 fill-pink-500">
                  <path
                    d="M88 0h80c13.3 0 24 10.7 24 24V64H64V24C64 10.7 74.7 0 88 0zM0 151.7c0-15.6 9-29.8 23.2-36.5l24.4-11.4c11-5.1 23-7.8 35.1-7.8h90.6c12.1 0 24.1 2.7 35.1 7.8l24.4 11.4c14.2 6.6 23.2 20.8 23.2 36.5c0 14.4-7.5 27-18.9 34.1c11.5 8.8 18.9 22.6 18.9 38.2c0 16.7-8.5 31.4-21.5 40c12.9 8.6 21.5 23.3 21.5 40s-8.5 31.4-21.5 40c12.9 8.6 21.5 23.3 21.5 40s-8.5 31.4-21.5 40c12.9 8.6 21.5 23.3 21.5 40c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48c0-16.7 8.5-31.4 21.5-40C8.5 415.4 0 400.7 0 384s8.5-31.4 21.5-40C8.5 335.4 0 320.7 0 304s8.5-31.4 21.5-40C8.5 255.4 0 240.7 0 224c0-15.6 7.4-29.4 18.9-38.2C7.5 178.7 0 166.1 0 151.7zM64 240c0 8.8 7.2 16 16 16h96c8.8 0 16-7.2 16-16s-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zM80 352c-8.8 0-16 7.2-16 16s7.2 16 16 16h96c8.8 0 16-7.2 16-16s-7.2-16-16-16H80z" />
                </svg>
  
                <h1 class="text-xl  pl-12">2LTR</h1>
              </div>
        
        
            </div>
          </div>
          <div
            class="bg-red-200   w-56 h-60 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
            <div class="justify-center">
              <div class="text-blue ml-4 text-3xl font-extrabold font-mono pt-4">Steps</div>
              <div class=" pt-8">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" class="w-16 h-16 fill-pink-500">
                  <path
                    d="M256 48c0 26.5-21.5 48-48 48s-48-21.5-48-48s21.5-48 48-48s48 21.5 48 48zM126.5 199.3c-1 .4-1.9 .8-2.9 1.2l-8 3.5c-16.4 7.3-29 21.2-34.7 38.2l-2.6 7.8c-5.6 16.8-23.7 25.8-40.5 20.2s-25.8-23.7-20.2-40.5l2.6-7.8c11.4-34.1 36.6-61.9 69.4-76.5l8-3.5c20.8-9.2 43.3-14 66.1-14c44.6 0 84.8 26.8 101.9 67.9L281 232.7l21.4 10.7c15.8 7.9 22.2 27.1 14.3 42.9s-27.1 22.2-42.9 14.3L247 287.3c-10.3-5.2-18.4-13.8-22.8-24.5l-9.6-23-19.3 65.5 49.5 54c5.4 5.9 9.2 13 11.2 20.8l23 92.1c4.3 17.1-6.1 34.5-23.3 38.8s-34.5-6.1-38.8-23.3l-22-88.1-70.7-77.1c-14.8-16.1-20.3-38.6-14.7-59.7l16.9-63.5zM68.7 398l25-62.4c2.1 3 4.5 5.8 7 8.6l40.7 44.4-14.5 36.2c-2.4 6-6 11.5-10.6 16.1L54.6 502.6c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L68.7 398z" />
                </svg>

              <h1 class="text-xl  pl-12">3000</h1>
              </div>
        
        
            </div>
          </div>
        </div>


      </section>
     
      <!------------end new section------->

      <div>
        <section class="h-screen">
          <div class="container px-6 h-full">
            <div class="flex justify-center items-center flex-wrap h-full g-6 text-gray-800">
              <div class="md:w-8/12 lg:w-6/12 mb-12 md:mb-0">
                <img src="images/work-create-remove.png" />
              </div>
              <div class="md:w-8/12 lg:w-5/12 lg:ml-20">
      
                <!-- <div>
                          <h1 class=" text-2xl font-mono font-extrabold text-center">Recently Added Workouts</h1>
                        </div>  -->
                <div
                  class="flex justify-between bg-purple-300 w-full py-5 rounded overflow-hidden shadow-md hover:shadow-lg shadow-gray-500/50  mb-8 mx-auto ">
                  <div class="text-white ml-4 text-xl font-extrabold font-mono "> Hip Thrust </div>
      
                  <div class="text-white text-xl font-extrabold font-mono ">
                    <p> 3 Sets </p>
                  </div>
                  <div class="text-white text-xl font-extrabold font-mono ">
                    <p> 6 Reps </p>
                  </div>
                  <div class="text-white  text-xl font-extrabold font-mono ">
                    <p> 60 Seconds rest </p>
                  </div>
      
                  <div>
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                      class="w-6 h-6 fill-red-500 mr-4 cursor-pointer">
                      <path
                        d="M432 32H312l-9.4-18.7A24 24 0 0 0 281.1 0H166.8a23.72 23.72 0 0 0-21.4 13.3L136 32H16A16 16 0 0 0 0 48v32a16 16 0 0 0 16 16h416a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16zM53.2 467a48 48 0 0 0 47.9 45h245.8a48 48 0 0 0 47.9-45L416 128H32z" />
                    </svg>
                  </div>
      
                </div>
      
              </div>
            </div>
          </div>
        </section>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "Profile",
  layout: "main"

};
</script>

<style>

</style>



<!-- <template>
  <div class="flex h-screen">
    <Navigation />

    <div class="flex-1">
      <Nuxt />
      <div class="py-16">
        <FooterTracker />

      </div>

    </div>
  </div>

</template>

<script>
import Navigation from '../../components/Navigation.vue';
import FooterTracker from '../../components/FooterTracker.vue';

export default {
  name: 'DefaultLayout',
  components: {
    Navigation,
    FooterTracker
  }

}
</script>

<style>

</style> -->
