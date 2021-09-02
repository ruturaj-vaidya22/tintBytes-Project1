<template>
        <div class="bg-white py-10 rounded overflow-hidden shadow-md hover:shadow-lg">
            <h2 class="flex justify-center font-extrabold text-4xl">CONTACT</h2>
        </div>
        <div class="grid grid-cols-2 bg-white pb-10 px-10 rounded shadow-md hover:shadow-lg  justify-center  h-72 md:h-96 sm:pb-10 "> 
            <div class=" bg-cover bg-center h-full w-full">
                <textarea class="rounded-lg" name="message" id="message" cols="30" rows="10" placeholder="Message"></textarea>
                <div class="mt-6"> 
                    <button class="bg-green-600 text-secondary-900 text-white p-2 rounded py-2 px-3 uppercase text-md cursor-pointer tracking-wider hover:shadow-inner transform hover:scale-125 hover:opacity-50 transition ease-out duration-300">Send</button>
                </div>
            </div>
            <div class="bg-green-700 p-10 text-white">
                <h2 class="font-bold text-xl">Address :-</h2>
                <hr class="border-2 my-6 border-white">
                <div> 
                    <div>
                        <svg class="w-6 h-6 inline-block" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        <span> Full Address</span>
                    </div> 
                    <div class="mt-4">
                        <svg class="w-6 h-6 inline-block" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        <span> E: test@test.com</span>
                    </div>
                    <div class="mt-4">
                        <svg class="w-6 h-6 inline-block" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                        <span> P: #00-0000/0000000000</span>
                    </div>   
                    <div class="mt-4">
                        <svg class="w-6 h-6 inline-block" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span> W: www.test.com</span>
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
