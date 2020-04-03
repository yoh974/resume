<template>
    <div>
        <div>{{info.name}}</div>
        <div>{{info.firstname}}</div>
        <div>{{info.email}}</div>
    </div>
</template>

<script>
    export default {
        props:['info'],
        name: "Info"
    }
</script>

<style scoped>

</style>