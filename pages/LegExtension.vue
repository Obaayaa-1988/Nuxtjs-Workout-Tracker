<template>
    <div>
        <div class="flex justify-between py-8">
            <nuxt-link to="/OneLegSquat">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                    class="w-10 h-10 font-extrabold cursor-pointer">
                    <path
                        d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z" />
                </svg>
            </nuxt-link>

            <div class="font-bold text-2xl font-mono"> {{ new Date }}</div>
            <nuxt-link to="/">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"
                    class="w-10 h-10 font-extrabold cursor-pointer">
                    <path
                        d="M190.5 66.9l22.2-22.2c9.4-9.4 24.6-9.4 33.9 0L441 239c9.4 9.4 9.4 24.6 0 33.9L246.6 467.3c-9.4 9.4-24.6 9.4-33.9 0l-22.2-22.2c-9.5-9.5-9.3-25 .4-34.3L311.4 296H24c-13.3 0-24-10.7-24-24v-32c0-13.3 10.7-24 24-24h287.4L190.9 101.2c-9.8-9.3-10-24.8-.4-34.3z" />
                </svg>
            </nuxt-link>

        </div>




    </div>
</template>

<script>
export default {
    name: "LegExtension",
    layout: "main"

}
</script>

<style>

</style>