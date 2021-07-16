<template>

    <Chat />
    <!--<app-layout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Find Friends
            </h2>
        </template>

        
    </app-layout> -->
</template>

<script>
    
    import AppLayout from '@/Layouts/AppLayout'
    import Chat from '@/Pages/Chat'
   

    export default {
        components: {
            AppLayout,
            Chat
        },
       
    }
</script>



