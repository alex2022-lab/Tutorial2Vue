<template>
    <button v-on:click="contador++">Haz clic en mi</button>
    <p>Haz hecho clic {{ contador }} veces.</p>
</template>

<script>
export default{
    data() {
        return {
            contador: 0
        }
    }
}
</script>