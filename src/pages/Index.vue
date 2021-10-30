<template>
    <main-layout>
        <div class="grid gap-4 sm:grid-cols-2">
            <div class="col-span-2 text-center p-8 sm:p-16 ">
                <h2 class="text-xl sm:text-5xl font-bold text-blue-400">
                    Our <span class="text-gray-600">Focus</span>
                </h2>
                <p class="mt-3 text-lg text-gray-500">
                    Our long-term determination is the advancement of innovative standards in our communities, through creation
                    of cutting-edge systems and design of modern techniques to solve prevalent social problems.
                </p>        
            </div>

            <div class="col-span-2 sm:flex sm:flex-row-reverse">
                <div class="w-full text-center my-auto text-lg sm:px-8 sm:text-3xl text-gray-600 py-3">Climate change and sustainability management.</div>
                <img class="max-h-96 w-full sm:w-1/2" src="/images/climate.jpg" alt="">
            </div>

            <div class="col-span-2 sm:flex">
                <div class="text-center my-auto text-lg sm:px-8 sm:text-3xl text-gray-600 py-3">Agricultural value chain development and upward mobility.</div>            
                <img class="max-h-96 w-full sm:w-1/2" src="/images/agric.jpg" alt="">
            </div>

            <div class="col-span-2 sm:flex sm:flex-row-reverse">
                <div class="text-center my-auto text-lg sm:px-8 sm:text-3xl text-gray-600 py-3">Food sustainability and cyclical economy.</div>            
                <img class="max-h-96 w-full sm:w-1/2" src="/images/food.jpg" alt="">
            </div>
                    
            <div class="col-span-2 sm:flex">
                <div class="text-center my-auto text-lg sm:px-8 sm:text-3xl text-gray-600 py-3">Predominantly solving social problems at the grassroot using diverse approaches that is tailored
                    to specific demography.
                </div> 
                <img class="max-h-96 w-full sm:w-1/2" src="/images/agric1.jpg" alt="">
            </div>

        </div>
    </main-layout>
</template>

<script>
import MainLayout from "../layouts/MainLayout.vue";

export default {
    name: 'Index',
    components: {
        MainLayout,
    },
    props: {

    },
    data() {
        return {

        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
