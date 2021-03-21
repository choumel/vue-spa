<template>
    <div id="app">
        <h3> {{title}}</h3>
        <character> </character>
    </div>
</template>

import character from './components/character.vue'

<script>
import character from './components/character.vue'
    export default {
        name:'app',
        data(){
            return {
                title: 'Generate Your Team'
            }
        },
        components: {
            character
        }
    }

</script>
