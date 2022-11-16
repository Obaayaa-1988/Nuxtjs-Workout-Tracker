<template>
    <div class="flex h-screen">
        <NavigateWorkout />

        <div class="flex-1 overflow-hidden flex flex-col ">
            <div class="flex-1 overflow-y-auto">
                <Nuxt />

            </div>
            <div>
                <FooterTracker />

            </div>

        </div>
    </div>

</template>

<script>
import NavigateWorkout from '~/components/NavigateWorkout.vue';
import FooterTracker from '~/components/FooterTracker.vue';

export default {
    name: 'MainLayout',
    components: {
        NavigateWorkout,
        FooterTracker
    }

}
</script>

<style>

</style>
