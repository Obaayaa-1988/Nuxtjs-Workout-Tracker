<template>
    <div class="flex h-screen">
        <Navigation />

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
import Navigation from '~/components/Navigation.vue';
import FooterTracker from '~/components/FooterTracker.vue';

export default {
    name: 'MainLayout',
    components: {
        Navigation,
        FooterTracker
    }

}
</script>

<style>

</style>
