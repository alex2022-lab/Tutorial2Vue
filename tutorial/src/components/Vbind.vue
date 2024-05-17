<template>
    <button v-bind:disabled="botonDeshahilitado">Haz clic en mi</button>
</template>

<script>
export default{
    data() {
        return {
            botonDeshahilitado: true
        }
    }
}

</script>