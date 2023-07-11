<template>
    <div class="box has-text-weight-bold" :style="estilos">
        <slot></slot>

    </div>
</template>

<script lang="ts">
import { defineComponent }  from 'vue'

export default defineComponent({
    name: 'Box',
    data () {
        return {
            estilos: { //outra opção para estilização, via JS. *:style="estilos"* 
                background: '#FAF0CA'
            }
        }
    }
});
</script>