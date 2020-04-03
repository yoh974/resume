<template>
    <div>
        <div>{{proXp.id}}</div>
        <div>{{proXp.years}}</div>
        <div>{{proXp.description}}</div>
    </div>
</template>

<script>
    export default {
        props:['proXp'],
        name: "ProXP"
    }
</script>

<style scoped>

</style>