<template>
    <div>
        <p>Isso é um teste de componente!!</p>

        <p>Voce digitou: {{valor}} </p>

        <input type="text=" v-model="valor">

    </div>
</template>

<script>
    export default {
        name: "teste",
        data: function () {
            return {
                valor:""
            }
        }
    }
</script>

<style scoped>

</style>