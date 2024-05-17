<template>
    <ul>
        <li v-for="item in lista" :key="item.id">
        {{ item.nombre }}</li>
    </ul>
</template>

<script>
export default{

    data() {
        return {
            lista: [
                {id: 1, nombre: 'item 1'},
                {id: 2, nombre: 'item 2'},
                {id: 3, nombre: 'item 3'}
            ]
        }
    }
}
</script>