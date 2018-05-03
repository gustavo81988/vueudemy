<template>
    <div>
        <p>Counter is: {{ dobuleCounter }}</p>
        <p>Numbre of Clicks {{ stringCounter }}</p>
    </div>
</template>

<script>
    import { mapGetters } from 'vuex'
    export default {
        computed: {
            ...mapGetters([
                    'dobuleCounter',
                    'stringCounter'
            ])
        }
    }
</script>
