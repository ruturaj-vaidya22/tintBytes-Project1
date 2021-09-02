<template>
    <div>
        This is about me page
        <div v-show="isActive">
            <slot></slot>
        </div>
    </div>
</template>

<script>
    import { defineComponent, onMounted } from 'vue'
    import JetApplicationLogo from '@/Jetstream/ApplicationLogo.vue'

    export default defineComponent({
        components: {
            JetApplicationLogo,
        },
        props:{
            name:{ required: true },
            selected: { default: false }
        },
        
        setup(props) {
            
            onMounted(() => {
                 const isActive = this.selected
            })

            return{
                isActive
            }
        }
    })
</script>

<style scoped>

</style>