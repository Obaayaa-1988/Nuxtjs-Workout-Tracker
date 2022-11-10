<template>
  <div>
    <div >
      <div class="h-2/4 w-full  rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50  ">
        <div class="flex justify-around">

          <div>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
              class="w-6 h-6 font-extrabold mt-28" >
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
            </svg>
 

          </div>
          <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
            Hi, Ashbella
          </h2>
          

          <div class="bg-indigo-200 h-40 w-40 rounded-full">
            <img src="images/lady.jpg" alt="PanCake" class="w-32 h-32 object-cover rounded-full mt-12" />
          </div>
        </div>
      </div>

      <main class="px-16 py-6 md:col-span-2">
        <div class="flex justify-center md:justify-end">
          
        </div>

        <header>
          <h3 class="text-2xl font-bold py-12 font-mono">Pick Your WorkOut Days</h3>
        </header>

        <!------------------pick workout start-->


        <div
          class="h-1/4 w-full bg-indigo-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100  ">
          <div class="flex justify-around">
        
            <div class="text-center pt-20">
              <p class="font-bold font-mono text-lg">Wednesday 9TH November 2022</p>
            </div>

            <!---------dropdown  start-->

            <div> 
              <button id="dropdownCheckboxButton" data-dropdown-toggle="dropdownDefaultCheckbox"
                class="text-white bg-pink-600  hover:bg-blue-800 mt-20 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2.5 text-center inline-flex items-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                type="button">Pick A Workout Day <svg class="ml-2 w-4 h-4" aria-hidden="true" fill="none" stroke="currentColor"
                  viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                </svg></button>
              
              <!-- Dropdown menu -->
              <div id="dropdownDefaultCheckbox"
                class="hidden z-10 w-48 bg-white rounded divide-y divide-gray-100 shadow dark:bg-gray-700 dark:divide-gray-600"
                data-popper-reference-hidden="" data-popper-escaped="" data-popper-placement="bottom"
                style="position: absolute; inset: 0px auto auto 0px; margin: 0px; transform: translate(0px, 410px);">
                <ul class="p-3 space-y-3 text-sm text-gray-700 dark:text-gray-200" aria-labelledby="dropdownCheckboxButton">
                  <li>
                    <div class="flex items-center">
                      <input id="checkbox-item-1" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-1" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Monday</label>
                    </div>
                  </li>
                  <li>
                    <div class="flex items-center">
                      <input checked="" id="checkbox-item-2" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-2" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Tuesday</label>
                    </div>
                  </li>
                  <li>
                    <div class="flex items-center">
                      <input id="checkbox-item-3" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-3" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Wednesday
                        </label>
                    </div>
                  </li>

                  <li>
                    <div class="flex items-center">
                      <input id="checkbox-item-3" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-3" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Thursday</label>
                    </div>
                  </li>

                  <li>
                    <div class="flex items-center">
                      <input id="checkbox-item-3" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-3" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Friday</label>
                    </div>
                  </li>

                  <li>
                    <div class="flex items-center">
                      <input id="checkbox-item-3" type="checkbox" value=""
                        class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-700 focus:ring-2 dark:bg-gray-600 dark:border-gray-500">
                      <label for="checkbox-item-3" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Saturday</label>
                    </div>
                  </li>
                </ul>
              </div>

          
            </div>



            <!------------dropdown end-->
        
            <div >
              <img src="images/stopwatch-remove.png" alt="PanCake" class="w-44 h-44 object-cover rounded-full mt-8" />
            </div>

          </div>
        </div>

       

        <!-------------------------pick workout end-->


        <header>
          <h3 class="text-2xl font-bold pt-12 font-mono">Weekly Stats</h3>
        </header>



        <div>
          <div class="mt-8 grid lg:grid-cols-3">
            <!---cards here-->
              <div class="bg-red-100  cursor-pointer">
                <div class="flex justify-center pt-16">
                  <img src="images/legs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                </div>
                <div class="m-4">
                  <span class="font-semibold text-2xl font-mono">Legs</span>
                </div>
              </div>
           

            
              <div class=" bg-blue-200  overflow-hidden shadow-md hover:shadow-lg cursor-pointer">
                <div class="flex justify-center pt-16">
                  <img src="images/abs.png" alt="PanCake" class="w-36 h-36 object-cover" />
                </div>
                <div class="m-4">
                  <span class="font-semibold text-2xl font-mono">Abs</span>
                </div>
              </div>
           

           
              <div class=" bg-lime-200 overflow-hidden shadow-md relative hover:shadow-lg cursor-pointer">
                <div class="flex justify-center pt-16">
                  <img src="images/glutes.png" alt="PanCake" class="w-36 h-36 object-cover" />
                </div>
                <div class="m-4">
                  <span class="font-semibold text-2xl font-mono">Glutes</span>
                </div>
              </div>
           
            
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: "Profile",
  layout: "default"
  
};
</script>

<style>

</style>