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

      <section class="bg-gradient-to-r from-green-400 to-blue-500 w-full h-full  px-16 py-6 md:col-span-2 ">

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
      
      
          <nuxt-link to="/cardio">
            <div class="bg-white  w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center">
              <div class="justify-center">
                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">Set Workout Goals</div>
                <div class="pl-28 pt-8" >
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" class="w-16 h-16 fill-lime-400">
                    <path
                      d="M104 96H56c-13.3 0-24 10.7-24 24v104H8c-4.4 0-8 3.6-8 8v48c0 4.4 3.6 8 8 8h24v104c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V120c0-13.3-10.7-24-24-24zm528 128h-24V120c0-13.3-10.7-24-24-24h-48c-13.3 0-24 10.7-24 24v272c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V288h24c4.4 0 8-3.6 8-8v-48c0-4.4-3.6-8-8-8zM456 32h-48c-13.3 0-24 10.7-24 24v168H256V56c0-13.3-10.7-24-24-24h-48c-13.3 0-24 10.7-24 24v400c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V288h128v168c0 13.3 10.7 24 24 24h48c13.3 0 24-10.7 24-24V56c0-13.3-10.7-24-24-24z" />
                  </svg>
                 
                </div>
      
      
              </div>
      
            </div>
          </nuxt-link>
          <nuxt-link to="/cardio">
            <div class="bg-white   w-72 h-56 rounded-3xl overflow-hidden shadow-md relative hover:shadow-lg shadow-gray-500/50 cursor-pointer py-8 text-center  ">
              <div class="justify-center">
                <div class="text-blue ml-4 text-xl font-extrabold font-mono pt-4">Pick Calender</div>
                <div class="pl-28 pt-8"  >
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-16 h-16 fill-purple-600"  >
                    <path
                      d="M400 64h-48V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H160V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zm-6 400H54c-3.3 0-6-2.7-6-6V160h352v298c0 3.3-2.7 6-6 6z" />
                  </svg>
                </div>
      
      
              </div>
            </div>
          </nuxt-link>
      
        </div>

        <!---------------------added workouts section------->

        <div class="">
          <div> 
            <h1 class="text-white text-2xl font-mono font-extrabold text-center my-8">Recently Added Workouts</h1>
          </div>
          <div class="flex justify-between bg-purple-300 w-2/3 py-5 rounded overflow-hidden shadow-md hover:shadow-lg shadow-gray-500/50  mb-8 mx-auto ">
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
        
     
      
      </section>
     


      <!------------end new section------->
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
