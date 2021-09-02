<template>
    <app-layout title="Profile">
        <template >
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Company 
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <home-profile/>
                    <contact-profile/>
                    <about-profile/>
                </div>
            </div>
        </div>
    </app-layout>
</template>

<script>
    import { defineComponent } from 'vue'
    import AppLayout from '@/Layouts/AppLayout.vue'
    import HomeProfile from '../Jetstream/HomeProfile.vue'
    import ContactProfile from '../Jetstream/ContactProfile.vue'
    import AboutProfile from '../Jetstream/AboutProfile.vue'

    export default defineComponent({
        components: {
            AppLayout,
            HomeProfile,
            ContactProfile,
            AboutProfile,
        },

    
                    
    })
</script>
