<script>
export default {
     name: "AppTitle",
     data(){
        return{
            hello: 'Ciao'
        }
     },       
}
</script>

<template lang="">
    <div class="font">
        {{hello}}
        <img src="../assets/vue.svg" alt="">
    </div>
</template>

<style scoped>
    
</style>