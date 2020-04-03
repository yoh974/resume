<template>
    <div>
        <div>{{formation.id}}</div>
        <div>{{formation.years}}</div>
        <div>{{formation.description}}</div>
    </div>

</template>

<script>
    export default {
        props:['formation'],
        name: "Formation"
    }
</script>

<style scoped>

</style>