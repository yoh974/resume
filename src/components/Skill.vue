<template>
    <div>
        <div>{{skill.id}}</div>
        <div>{{skill.percent}}</div>
        <div>{{skill.name}}</div>
    </div>
</template>

<script>
    export default {
        props:['skill'],
        name: "Skill"
    }
</script>

<style scoped>

</style>