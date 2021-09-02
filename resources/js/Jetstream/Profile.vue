<template>
    <div class="h-full bg-gray-600 opacity-100 border-white grid grid-cols-4 gap-4 object-scale-down" > <!--style=" background-image: url('/images/profile.jpg');" -->
        <div class="col-start-2 col-span-2 bg-opacity-75 mt-10">           
            <!-- Cards go here -->
            <div class="overflow-hidden shadow-md relative hover:shadow-lg p-10 h-auto flex flex-wrap justify-center">
                <img src="/images/profile.jpg" alt="Profile Image" class="shadow rounded-full h-24 w-24 flex object-center object-cover border-none opacity-100"/>
            </div>
            <div class="bg-gray-900 opacity-75 border-b-2 border-white ">
                <h2 class="font-bold text-white flex justify-center">Mark Adrian</h2> 
                <block class=" font-semibold text-xs text-white flex justify-center">LONDON,UK</block>
            </div>

            <div class=" mt-4">
                <div class=" md:flex justify-between md:ml-10 md:mr-10 md:mt-8">
                    <div class="m-4 sm:mt-4 md:mt-0 ">                    
                        <div class="bg-gray-100 text-green-500 text-xs uppercase font-bold rounded-full py-3 px-6 opacity-50 tracking-wider hover:shadow-inner transform hover:scale-125 hover:opacity-100 transition ease-out duration-300">
                            <span>UI</span>
                        </div>
                    </div>
                <div class="mt-4 sm:mt-4 md:mt-0 ">
                        <div class="bg-gray-100 text-green-500 text-xs uppercase font-bold rounded-full py-3 px-6 opacity-50 tracking-wider hover:shadow-inner transform hover:scale-125 hover:opacity-100 transition ease-out duration-300">
                            <span>UX</span>
                        </div>
                </div>
                    <div class="mt-4 sm:mt-4 md:mt-0 ">
                        <div class="bg-gray-100 text-green-500 text-xs uppercase font-bold rounded-full py-3 px-6 opacity-50 tracking-wider hover:shadow-inner transform hover:scale-125 hover:opacity-100 transition ease-out duration-300">
                        <span>PHOTOSHOP</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="border-b-2 border-green-500 py-10 shadow-md hover:shadow-lg">
                <div class="flex justify-between md:ml-10 md:mr-10">
                    <div class="bg-secondary-100 text-secondary-200 text-xs uppercase font-bold rounded-full p-2">
                        <svg class="w-8 h-8 inline-block text-white hover:scale-125 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        <h2 class="mt-4 text-white">#9898</h2>
                    </div>

                    <div class="bg-secondary-100 text-secondary-200 text-xs uppercase font-bold rounded-full p-2">
                        <svg class="w-8 h-8 inline-block text-white hover:scale-125 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                        <h2 class="mt-4 text-white">#899</h2>
                    </div>

                    <div class="bg-secondary-100 text-secondary-200 text-xs uppercase font-bold rounded-full p-2">
                        <svg class="w-8 h-8 inline-block text-white hover:scale-125 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        <h2 class="mt-4 text-white">#897</h2>
                    </div>
                </div>
            </div>
            <div class="text-white p-10 border-b-2 border-white shadow-md hover:shadow-lg">
                    Laravel Jetstream provides a beautiful, robust starting point for your next Laravel application. Laravel is designed
                    to help you build your application using a development environment that is simple, powerful, and enjoyable. We believe
                    you should love expressing your creativity through programming, so we have spent time carefully crafting the Laravel
                    ecosystem to be a breath of fresh air. We hope you love it.
            </div>

            <div class="shadow-md hover:shadow-lg">
                <div class=" flex justify-between py-10 border-b-2 border-white md:ml-10 md:mr-10">
                    <svg class="w-6 h-6 hover:scale-150 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path></svg>
                    <svg class="w-6 h-6 hover:scale-150 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z"></path></svg>
                    <svg class="w-6 h-6 hover:scale-150 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10l-2 1m0 0l-2-1m2 1v2.5M20 7l-2 1m2-1l-2-1m2 1v2.5M14 4l-2-1-2 1M4 7l2-1M4 7l2 1M4 7v2.5M12 21l-2-1m2 1l2-1m-2 1v-2.5M6 18l-2-1v-2.5M18 18l2-1v-2.5"></path></svg>
                    <svg class="w-6 h-6 hover:scale-150 hover:opacity-100 transition ease-out duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10l-2 1m0 0l-2-1m2 1v2.5M20 7l-2 1m2-1l-2-1m2 1v2.5M14 4l-2-1-2 1M4 7l2-1M4 7l2 1M4 7v2.5M12 21l-2-1m2 1l2-1m-2 1v-2.5M6 18l-2-1v-2.5M18 18l2-1v-2.5"></path></svg>
                </div>
            </div>
            <div class="shadow-md hover:shadow-lg">
                <div class=" flex justify-center py-10 border-b-2 border-white md:ml-10 md:mr-10">
                    <button class="bg-green-600 text-secondary-900 text-white p-2 rounded py-2 px-3 uppercase text-md cursor-pointer tracking-wider hover:shadow-inner transform hover:scale-125 hover:opacity-50 transition ease-out duration-300">Follow</button>
                </div>
            </div>     
        </div>        
    </div>
</template>

<script>
    import { defineComponent } from 'vue'
    import JetApplicationLogo from '@/Jetstream/ApplicationLogo.vue'

    export default defineComponent({
        components: {
            JetApplicationLogo,
        },
    })
</script>

<style scoped>

</style>
