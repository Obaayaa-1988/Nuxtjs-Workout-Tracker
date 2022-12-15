<template>
  <div>
    <div
      class=" h-1/4 w-full bg-indigo-300 rounded-b-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-40 border border-gray-100 shadow-lg shadow-gray-500/50 md">
      <nuxt-link to="/Home">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-10 h-10 font-extrabold cursor-pointer">
          <path
            d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z" />
        </svg>
      </nuxt-link>
      <div class="flex justify-around">
        <h2 class="text-gray-700 text-4xl font-extrabold font-mono pt-28">
          ARMS WORKOUT
        </h2>
        <div></div>

        <div>
          <img src="images/arms.png" alt="PanCake" class="w-80 h-80 object-cover" />
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'ArmsWorkOut',
  layout: "main"


}
</script>


<style>

</style>