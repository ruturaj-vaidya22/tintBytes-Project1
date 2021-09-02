<template>
        <div class="bg-white py-10 rounded overflow-hidden shadow-md hover:shadow-lg">
            <h2 class="flex justify-center font-extrabold text-4xl">HOME</h2>
        </div>
        <div class="grid grid-cols-2 bg-white pb-10 px-10 rounded shadow-md hover:shadow-lg  justify-center  h-72 md:h-96 sm:pb-10 "> 
            <div class=" bg-cover bg-center h-full w-full" style="background-image: url('/images/profile.jpg')">
            </div>
            <div class="bg-green-700 p-10 text-white">
                <h2 class="font-bold text-xl">FUll Name</h2>
                <h2 class=" font-semibold text-lg">Location</h2>
                <hr class="border-2 my-6 border-white">
                <div> 
                    <table class="table-fixed">
                        <tr><td>D.O.B</td> <td><p class="ml-6 py-1">: 00-00-0000</p></td></tr>
                        <tr><td>PHONE</td> <td><p class="ml-6 py-2">: #000-00000</p></td></tr>
                        <tr><td>ADDRESS</td> <td><p class="ml-6">: Full Address</p></td></tr>
                        <tr><td>EMAIL</td> <td><p class="ml-6 py-2 ">: Email</p></td></tr>
                        <tr><td>WEBSITE</td> <td><p class="ml-6">: Website</p></td></tr>
                    </table>                   
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
