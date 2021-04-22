<template>
    <div class="ButtonChallenges">
        <div class="container">
            <button v-for="(button, key) in buttons" :key="key" :class="buttons.boton">
                <i>Default</i>
            </button>
        </div>
    </div>
</template>
<script>
export default {
    name: 'ButtonsChallenges',
    data(){
        return{
            buttons: {
                boton: [
                    'btn btn-secondary mx-1'
                    
                ],
                boton2: [
                    'btn btn-primary mx-1'
                ]
            },
            buttons2: [],
            buttons3: []
        }
    }
}
</script>
<style scoped>

</style>