<template>
    <span>
        <p>Server Status: {{status}}</p>
        <hr>
        <button @click="changeStatus">Change Status</button>
    </span>
</template>

<script>
    export default {
        data: function(){
            return {
                status: 'Critical'
            }
        },
        methods: {
            changeStatus(){
                this.status = 'Normal';
            }
        }

    }
</script>

<style>

</style>
