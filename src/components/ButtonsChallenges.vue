<template>
    <div class="ButtonChallenges">
        <div class="container mb-3">
            <button v-for="(button, key) in buttons" :key="key" :class="buttons">
                <i>Default</i>
            </button>
            <button v-for="(button2, key) in buttons2" :key="key" :class="buttons2">
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons3">
                <i>Default</i>
            </button>
            <button :class="buttons4">
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons5">
                <i>Default</i>
            </button>
            <button :class="buttons6">
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons7" disabledShadow>
                <i>Default</i>
            </button>
            <button :class="buttons8" disabledShadow>
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons9" disabled>
                <i>Default</i>
            </button>
            <button :class="buttons10" disabled>
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons11">
                <i>Default</i>
            </button>
            <button :class="buttons12">
                <i>Default</i>
            </button>
        </div>
        <div class="container mb-3">
            <button :class="buttons13">
                <i>Default</i>
            </button>
            <button :class="buttons14">
                <i>Default</i>
            </button>
            <button :class="buttons15">
                <i>Default</i>
            </button>
        </div>
                <div class="container mb-3">
            <button :class="buttons16">
                <i>Default</i>
            </button>
            <button :class="buttons17">
                <i>Default</i>
            </button>
            <button :class="buttons18">
                <i>Default</i>
            </button>
            <button :class="buttons19">
                <i>Default</i>
            </button>
        </div>
                <div class="container mb-3">
            <button :class="buttons20" disabled>
                <i>Default</i>
            </button>
            <button :class="buttons21" disabled>
                <i>Default</i>
            </button>
            <button :class="buttons22" disabled>
                <i>Default</i>
            </button>
            <button :class="buttons23" disabled>
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
            buttons: ['btn btn-secondary mx-1'],
            buttons2: ['btn btn-primary mx-1'],
            buttons3: ['btn btn-outline-warning mx-1'],
            buttons4: ['btn btn-outline-info mx-1'],
            buttons5: ['btn btn-text-success mx-1'],
            buttons6: ['btn btn-text-danger mx-1'],
            buttons7: ['btn btn-danger mx-1'],
            buttons8: ['btn btn-dark mx-1'],
            buttons9: ['btn btn-success mx-1'],
            buttons10: ['btn btn-text-warning mx-1'],
            buttons11: [`'btn btn-outline-success mx-1 startIcon='local_grocery_store''`],
            buttons12: [`'btn btn-outline-dark mx-1 endIcon='local_grocery_store''`],
            buttons13: ['btn btn-dark btn-sm mx-1'],
            buttons14: ['btn btn-dark btn-md mx-1'],
            buttons15: ['btn btn-dark btn-lg mx-1'],
            buttons16: ['btn btn-primary btn-block mx-1'],
            buttons17: ['btn btn-default btn-block mx-1'],
            buttons18: ['btn btn-secondary btn-block mx-1'],
            buttons19:['btn btn-danger btn-block mx-1'],
            buttons20:['btn btn-primary btn-block rounded mx-1'],
            buttons21:['btn btn-default btn-block rounded mx-1'],
            buttons22:['btn btn-secondary btn-block rounded mx-1'],
            buttons23:['btn btn-danger btn-block rounded mx-1'],
        }
    }
}
</script>
<style scoped>
.ButtonChallenges{
    background-color: slategray;
}
</style>